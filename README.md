# ICRA 2026 Project Page

A lightweight static page for your paper, inspired by common research project pages.

## Quick Start

- Open `index.html` and replace placeholders:
  - Title, authors, affiliations
  - Abstract + key points
  - Resource links (code, video, poster)
  - BibTeX entry
- The PDF is linked as `ICRA26_RX.pdf` in the repo root. Replace if needed.
- Figures are referenced as `fig1.png` … `fig7.png`. Swap or remove sections as needed.

## Local Preview

Open `index.html` directly in your browser, or serve locally:

- Python 3: `python3 -m http.server` and visit `http://localhost:8000`

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. In Settings → Pages, set Source to `main` branch, `/ (root)`.
3. The site will be available at `https://<your-username>.github.io/<repo>/`.

## Customization Tips

- Styles: edit `assets/css/main.css`.
- Social preview: update `<meta property="og:image" content="fig1.png" />` in `index.html`.
- Add or remove sections by editing `index.html`.

