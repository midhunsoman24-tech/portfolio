# portfolio

A single-file static digital business card for Midhun Soman. The site is a lightweight HTML page with two local images that can be opened locally or hosted as a static site.

## Run locally

- Open `index.html` in a browser, or run a simple static server:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy

This repository includes a GitHub Actions workflow (./github/workflows/pages.yml) that automatically publishes the site to GitHub Pages when changes are pushed to the `main` branch.

- After the workflow runs, the site will be available at:
  `https://midhunsoman24-tech.github.io/portfolio/` (the exact URL will be shown in the Pages settings once the site is published).

## Contents

- index.html — page markup (references styles.css)
- styles.css — extracted stylesheet
- profile.jpg, rareminds_logo.png — image assets

## Contact

- Email: midhunsoman24@gmail.com
