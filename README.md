# Enova Concepts website

Static rebuild of www.enovaconcepts.com (originally on Google Sites), hosted on GitHub Pages.

- `index.html` – Home
- `technology/`, `news/`, `team/`, `contact/` – other pages
- `home/` – redirect so the old Google Sites `/home` URL keeps working
- `assets/css/site.css` – all styling (accent color is `--accent`)
- `assets/img/` – images

Edit the HTML directly; every push to `main` redeploys via `.github/workflows/pages.yml`.
