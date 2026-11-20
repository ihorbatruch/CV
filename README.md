# Ihor Batruch — CV website

Static one-page CV site for GitHub Pages (no build step).

## Files
- `index.html` — the page
- `assets/css/style.css` — styles; change `--accent` at the top to recolour
- `CV.pdf` — full CV, linked from "Download CV" and the publications section
- `assets/img/` — put `portrait.jpg` here, then swap the placeholder in `index.html` (instructions in the comment there)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `CV`, or `<username>.github.io` for a root-level site).
2. Upload the contents of this folder (or push with GitHub Desktop / git).
3. Repository → Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. After a minute the site is live at `https://<username>.github.io/<repo>/`.
