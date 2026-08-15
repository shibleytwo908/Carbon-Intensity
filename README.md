# Carbon-Intensity

A mobile-friendly webapp showing the UK's 48-hour grid carbon intensity forecast
by region, using National Energy System Operator's (NESO) free Carbon Intensity
API (https://carbonintensity.org.uk).

## Files

- `index.html` — the entire app (HTML/CSS/JS in one file, no build step)
- `manifest.json` — web app manifest, enables "Add to Home Screen" installability
- `icons/` — app icons used by the manifest and iOS home screen

## Hosting

This is a static site — no server or build process needed. It's hosted via
GitHub Pages directly from this repository. Any push to the `main` branch
updates the live site within a minute or two.

## Updating the app

To make changes: edit `index.html` directly on GitHub (pencil icon on the file
page → edit → commit), or upload a replacement file via **Add file → Upload
files** on the repo's main page.

## Data source

All data comes live from the NESO Carbon Intensity API
(https://api.carbonintensity.org.uk), called directly from the browser. There
is no backend or API key.
