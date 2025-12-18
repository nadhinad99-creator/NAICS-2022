# NAICS (2022) Search — GitHub Pages

This static page provides a fast client-side search over your curated **2022 NAICS** dataset.

## Files
- `index.html` — the search UI and logic (pure JS, no build step).
- `naics_2022_from_nadhirah.json` — your dataset (place alongside `index.html`).

## How to use
1. Put both files in your GitHub Pages repository (e.g., `NAICS-2022/`).
2. Commit & push; GitHub Pages will serve the site.
3. Open the page and search by **6-digit code** or **keywords**.

## Guardrails
- The page **only** shows codes present in your dataset.
- Legacy code **454110** is blocked with a guidance message.

## Optional
- To change the JSON path, edit `const DATA_URL` near the top of `index.html`.
