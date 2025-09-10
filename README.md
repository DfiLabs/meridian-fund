# Meridian Fund Website

This repository contains the source code for the **Meridian Fund** website. The site presents an overview of the multi‑strategy crypto fund managed by DFi Labs, including strategy books, performance metrics, risk management practices, governance structure and team bios.

## Structure

The site is built as a single‑page application using simple HTML and CSS:

- **index.html** – the primary content of the site
- **style.css** – styles and layout
- **images/** – team headshots and the logo
- **.github/workflows/pages.yml** – GitHub Actions workflow that automatically deploys the site to GitHub Pages when changes are pushed to the `main` branch
- **.nojekyll** – disables Jekyll processing on GitHub Pages

## Deployment

After committing and pushing to the `main` branch, GitHub Pages will automatically build and publish the site via GitHub Actions. The resulting website will be accessible at `https://<username>.github.io/meridian-fund/` (for user accounts) or `https://<org>.github.io/meridian-fund/` (for organizations).