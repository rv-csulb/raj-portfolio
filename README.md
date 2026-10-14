# Rajveer Verma — Engineering Portfolio

A responsive, single-page portfolio for GitHub Pages. It uses plain HTML, CSS and JavaScript, with no build step or external libraries.

## Preview locally

Open `index.html` in a browser, or run a local static server from this directory:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before publishing

1. Confirm the name shown in `index.html`.
2. Confirm the email, phone and LinkedIn links in the contact section.
3. Add more technical photos and outcomes as they are available. The current Theseus photos are optimized WebP copies in `assets/theseus/`; they show the workshop and launch site, while the silent walkthrough video shows the wiring harnesses and connectors. Schedule I is labeled as a work in progress, so update its case study as the PCB and system integration develop.
4. Add future images and videos under `assets/` and update the matching project section. Use media you have permission to publish.

## Publish with GitHub Pages

1. Create a GitHub repository for the site and add these files to its root.
2. Push the default branch (commonly `main`).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

GitHub Pages will show the published URL in the Pages settings. Relative paths keep the site compatible with both a user site and a project site.
