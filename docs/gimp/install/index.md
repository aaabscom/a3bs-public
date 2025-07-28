---
layout: install
title: GIMP Installation on Debian 13
---
# Install GIMP 3.0.4 on Debian 13

This guide walks through building and installing **GIMP 3.0.4** from source on **Debian 13 (Trixie)** using a clean prefix install at `$HOME/gimp-install`.

---

## Prerequisites

```bash
sudo apt update && sudo apt install -y \
  build-essential \
  meson \
  ninja-build \
  gettext \
  git \
  pkg-config \
  libtool \
  cmake \
  bison \
  flex \
  python3 \
  python3-pip \
  libgirepository1.0-dev \
  gobject-introspection \
  libjson-glib-dev \
  libgtk-3-dev \
  libgegl-dev \
  libbabl-dev \
  libgdk-pixbuf2.0-dev \
  libglib2.0-dev \
  libgexiv2-dev \
  liblcms2-dev \
  libpoppler-glib-dev \
  libxmu-dev \
  libxext-dev \
  libxfixes-dev \
  libtiff-dev \
  libjpeg-dev \
  libwebp-dev \
  libwebpmux3 \
  libwebpdemux2 \
  libarchive-dev \
  libopenjp2-7-dev \
  iso-codes \
  appstream-util \
  glib-compile-resources \
  glib-genmarshal \
  gettext \
  desktop-file-utils
```

Ensure the following runtime tools are available:

```bash
sudo apt install -y \
  appstream \
  appstream-glib \
  xdg-utils \
  dbus-x11
```

---

## Set Environment Variables

Add these lines to your `~/.bashrc` or run in the current shell:

```bash
export PATH="$HOME/gimp-install/bin:$PATH"
export PKG_CONFIG_PATH="$HOME/gimp-install/lib/x86_64-linux-gnu/pkgconfig:$PKG_CONFIG_PATH"
export XDG_DATA_DIRS="$HOME/gimp-install/share:$XDG_DATA_DIRS"
```

---

## Build GEGL (required)

```bash
git clone https://gitlab.gnome.org/GNOME/gegl.git
cd gegl
git checkout 0.4.63
meson setup _build --prefix=$HOME/gimp-install
ninja -C _build
ninja -C _build install
```

---

## Build GIMP 3.0.4

```bash
git clone https://gitlab.gnome.org/GNOME/gimp.git gimp-3.0.4
cd gimp-3.0.4
git checkout 3.0.4
meson setup --wipe _build \
  --prefix=$HOME/gimp-install \
  --buildtype=release \
  --pkg-config-path=$HOME/gimp-install/lib/x86_64-linux-gnu/pkgconfig
ninja -C _build
ninja -C _build install
```

---

## Launch GIMP

```bash
$HOME/gimp-install/bin/gimp-3.0
```

You may want to symlink it:

```bash
ln -s $HOME/gimp-install/bin/gimp-3.0 ~/bin/gimp3
```

---

## Notes

- If the build fails at the introspection phase (`.gir` files), ensure GEGL and its GIR files are correctly installed to `$XDG_DATA_DIRS`.
- Optional plug-ins and formats (e.g., JPEG-XL, OpenEXR) require additional libraries and development packages.
- GIMP plug-ins should be placed in: `~/.config/GIMP/3.0/plug-ins/`

---

## Optional: Verify Plugins Directory

```bash
ls ~/.config/GIMP/3.0/plug-ins/
```

---

## Troubleshooting

- If a `Gegl-0.4.gir` or similar include cannot be found, verify it was installed under `gimp-install/share/gir-1.0/`
- Use `meson configure _build` to inspect and adjust options
- Build logs are in `_build/meson-logs/`

---

© 2025 A Cubed Business Solutions. MIT License.

