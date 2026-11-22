# Witch's Atelier Wiki

Player wiki for Witch's Atelier, a NeoForge 1.21.1 Minecraft mod where spells are drawn as glyphs.

The site is built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and published to GitHub Pages
by the workflow in `.github/workflows/deploy.yml` on every push to `main`.

## Local preview

```bash
python -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/mkdocs serve
```

Pages live in `docs/`. The navigation is set in `mkdocs.yml`.
