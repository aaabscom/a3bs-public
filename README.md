# A³BS GIMP 3 Documentation

Public documentation for A Cubed's GIMP 3 automation tools and plugins. Expectations include structured, versioned documentation for the GIMP 3 Python plugin ecosystem created by **A Cubed Business Solutions** (A³BS).

📘 [View Live Docs](https://aaabscom.github.io/a3bs-public/)

> ⭐ If you find this project helpful, please consider [starring it](https://github.com/aaabscom/a3bs-public) to support visibility and development!
>
> [![GitHub stars](https://img.shields.io/github/stars/aaabscom/a3bs-public.svg)](https://github.com/aaabscom/a3bs-public/stargazers)

[![Support A³BS on Ko-fi](https://img.shields.io/badge/Support%20A³BS%20on%20Ko--fi-0f6065?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/aaabscom)

Help support the A³BS GIMP 3 documentation project!  
Every donation helps us build better tools for the open-source creative community. 🙌


## 📂 Structure

```plaintext
a3bs-public/
├── _config.yaml           # GitHub Pages config
├── index.md               # Main landing page (merged intro + links)
├── assets/                # Site assets (CSS, images, favicon, etc.)
│   ├── css/
│   └── images/
├── docs/
│   ├── index.md           # GIMP Architecture index (linked from root)
│   ├── gimp-arch/         # Auto-documented GIMP classes (Gegl, Gimp, GimpUi)
│   │   ├── Gegl/
│   │   ├── Gimp/
│   │   └── GimpUi/
│   ├── install/           # GIMP 3 install guides
│   └── overviews/         # Plugin overviews and summaries
├── manifest.log           # Tracks cleaned file revisions
└── README.md              # Repo overview and contribution guide
```

## 🔄 Workflow

- All changes originate in the `a3bs-dirty/` folder.
- Only explicitly cleaned or verified files are moved to `a3bs-clean/`.
- Unchanged files are moved (not copied).
- Cleaned files are committed as part of Baseline 0 and beyond.

## 🛠️ Jekyll Setup

This site is deployed via GitHub Pages using the [Minima](https://github.com/jekyll/minima) theme.
Ensure the following exists at the repo root:

- `_config.yml` with `theme: minima`
- `index.md` as your site landing page

## 🧼 Current Status

Baseline 0 committed. `a3bs-clean/` is fully synchronized and documented.


📄 View the live docs site: [GitHub Pages](https://aaabscom.github.io/a3bs-public/)

---

This repo contains:

- Class documentation
- Plugin introspection utilities
- Batch workflows and image tools

---

Built with care by **D & G**.
