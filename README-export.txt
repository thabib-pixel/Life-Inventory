LIFE TRACKER v21.0 — GITHUB PAGES RELEASE

Version: v21.0
Data baseline: life-tracker-v20_0-edited-inventory-data.json (user's latest v20.0 edited inventory export)
Records: Beauty 520; Closet 202; Home 30; Outfits 1.
The authoritative latest data includes 520 Beauty records, not the previous 526.
5 Beauty records were added and 11 removed. These deletions were respected.
Closet Bottoms 25 and Accessories Bags 15 / Hats 8 are retained.

DEPLOYMENT
1. Extract this ZIP and upload all root files + images/ to the GitHub Pages repository root.
2. Do NOT delete the images folder or upload only index.html.
3. Open your site in a browser; a loading message appears while the inventory JSON is downloaded.
4. Verify the counts, an edit, and reload on the published site.
5. Keep a backup copy of your latest edited inventory JSON; future exports are the source of truth.

Version-scoped v21 IndexedDB prevents old v20 saved browser copies from hiding or overwriting the new inventory.
The browser fetch revalidates cached inventory data, which can speed up repeat visits.

See QA-v21.0-results.txt for test details and limitations.
