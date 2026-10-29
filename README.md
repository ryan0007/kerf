# Kerf

Public home of the Kerf marketing site and desktop downloads. The app's source lives in a private repository.

- `site/`: the marketing site, plain static files with no build step. Pushing to `main` publishes it to GitHub Pages
  (`.github/workflows/pages.yml`). Preview locally with `python -m http.server -d site`.
- Releases: the Windows builds. They are uploaded here by the private repository's `release.yml` when a `v*` tag is
  pushed there; nothing is built in this repo.

Copy rules for the site: say only what is built, state that the app is unreleased or in preview, and give no prices
(tiers are not decided).
