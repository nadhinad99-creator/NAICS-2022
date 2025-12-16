
NAICS-2022 GitHub Pages Package
================================

Files:
- index.html — the public page that loads the CSV and renders a searchable table
- naics_2022_6digit_with_links.csv — the NAICS 2022 6-digit dataset with titles, descriptions, hierarchy, and NAICS.com links

How to publish:
1) Create or open your repo on GitHub (e.g., NAICS-2022) and ensure GitHub Pages is enabled:
   Settings → Pages → Source: Deploy from a branch, Branch: main, Folder: /(root)
2) Upload BOTH files (index.html and naics_2022_6digit_with_links.csv) to the ROOT of the repo.
3) Visit https://<your-username>.github.io/NAICS-2022/ to see the page.

If you rename the repo or put files in a subfolder, update the CSV path inside index.html (const CSV_PATH).
