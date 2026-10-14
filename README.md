# Rajinder Ashan

A minimal personal website. The site is self-contained in `dist/index.html` and needs no build step.

## GitHub Pages

Push this directory to a GitHub repository with `main` as the default branch. In the repository's Settings → Pages, set the source to GitHub Actions. The included workflow deploys `dist/` on every push to `main` and can also be run manually.

Only `dist/` is published. The `.openai/hosting.json` file records the separate Sites deployment.
