# flowly.net

The public website of [Flowly](https://app.flowly.net): plain HTML and CSS, no build step.

Push to `main` and `.github/workflows/publish.yml` publishes the site to the `gh-pages` branch, which
GitHub Pages serves at https://flowly.net (custom domain from `CNAME`).

Preview locally with `python3 -m http.server` in this folder. Screenshots in `assets/` come from the app
with demo data.
