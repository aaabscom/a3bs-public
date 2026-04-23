---
layout: install
title: GIMP Installation on Debian 13
---

# GIMP 3.2.4 (Custom Build + GI Integration)

This guide documents a full source build of **GIMP 3.2.4** with:

- Custom install prefix  
- Working GEGL + BABL  
- Functional GObject Introspection (GI)  
- Python (`gi.repository`) correctly bound to the custom build  
- Clean `.bashrc` environment management  

---

## 🧠 Goal

Ensure the following are all aligned:

- GIMP binary  
- Shared libraries  
- GI typelibs  
- Python GI bindings  
- Development tools (e.g., PyCharm)  

---

## 📦 Install Dependencies

```bash
sudo apt update

sudo apt install -y \
  build-essential meson ninja-build pkg-config \
  libglib2.0-dev libgtk-3-dev \
  libjpeg-dev libpng-dev libtiff-dev \
  liblcms2-dev libmypaint-dev \
  libjson-glib-dev libxml2-dev \
  libgexiv2-dev libpoppler-glib-dev \
  libbz2-dev liblzma-dev \
  python3-gi \
  gobject-introspection libgirepository1.0-dev
```

> ⚠️ Debian Trixie may have broken `libappstream-dev`. We build AppStream manually below.

---

## 📁 Set Install Prefix

```bash
export GIMP_PREFIX="$HOME/gimp-3.2.4"
```

---

## 🧱 Build BABL

```bash
cd ~/tmp
git clone https://gitlab.gnome.org/GNOME/babl.git
cd babl

meson setup build --prefix=$GIMP_PREFIX
ninja -C build
ninja -C build install
```

---

## 🧱 Build GEGL

```bash
cd ~/tmp
git clone https://gitlab.gnome.org/GNOME/gegl.git
cd gegl

meson setup build --prefix=$GIMP_PREFIX
ninja -C build
ninja -C build install
```

---

## 🧱 Build curl (required for AppStream)

```bash
cd ~/tmp
wget https://curl.se/download/curl-8.6.0.tar.gz
tar -xf curl-8.6.0.tar.gz
cd curl-8.6.0

./configure --prefix=$GIMP_PREFIX --with-openssl
make -j$(nproc)
make install
```

---

## 🧱 Build libfyaml

```bash
cd ~/tmp
git clone https://github.com/pantoniou/libfyaml.git
cd libfyaml

./bootstrap.sh
./configure --prefix=$GIMP_PREFIX
make -j1
make install
```

---

## 🧱 Build AppStream

```bash
cd ~/tmp
git clone https://github.com/ximion/appstream.git
cd appstream

export PKG_CONFIG_PATH="$GIMP_PREFIX/lib/pkgconfig:$PKG_CONFIG_PATH"

meson setup build --prefix=$GIMP_PREFIX
ninja -C build
ninja -C build install
```

---

## 🎨 Build GIMP 3.2.4

```bash
cd ~/tmp
git clone https://gitlab.gnome.org/GNOME/gimp.git
cd gimp

git checkout GIMP_3_2_4
git submodule update --init

meson setup build --prefix=$GIMP_PREFIX
ninja -C build
ninja -C build install
```

---

## ⚙️ Environment Setup (.bashrc)

Add this managed block:

```bash
# === A3BS MANAGED BLOCK (BEGIN) ===

export GIMP_PREFIX="$HOME/gimp-3.2.4"

export PATH="$GIMP_PREFIX/bin:$PATH"

export LD_LIBRARY_PATH="$GIMP_PREFIX/lib/x86_64-linux-gnu:$GIMP_PREFIX/lib"

export PKG_CONFIG_PATH="$GIMP_PREFIX/lib/pkgconfig:$GIMP_PREFIX/lib/x86_64-linux-gnu/pkgconfig"

export GI_TYPELIB_PATH="$GIMP_PREFIX/lib/x86_64-linux-gnu/girepository-1.0:/usr/lib/x86_64-linux-gnu/girepository-1.0"

alias gimp3="$GIMP_PREFIX/bin/gimp-3.2"

# === A3BS MANAGED BLOCK (END) ===
```

Reload:

```bash
source ~/.bashrc
```

---

## 🧪 Verification

### 1. Binary

```bash
gimp3 --version
```

Expected:

```
GNU Image Manipulation Program version 3.2.4
```

---

### 2. Linking

```bash
ldd $(which gimp3) | grep gimp
```

Expected:

```
/home/<user>/gimp-3.2.4/...
```

---

### 3. GI (Python)

```bash
python3 -c "
import gi
gi.require_version('GIRepository','2.0')
gi.require_version('Gimp','3.0')
from gi.repository import GIRepository, Gimp
print(GIRepository.Repository.get_default().get_typelib_path('Gimp'))
"
```

Expected:

```
/home/<user>/gimp-3.2.4/.../Gimp-3.0.typelib
```

---

## ✅ Result

You now have a fully aligned GIMP development environment with working GI integration.
