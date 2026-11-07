Life Tracker v22.0 — GitHub Pages static files

Baseline: life-tracker-v21_0-edited-inventory-data (2).json (most recent user export)
Inventory: Beauty 535 records; Closet 202 records; Home 30 records; Outfits 1 record.
The current Beauty/Home edits and all Closet items are preserved.

Deploy: unzip, upload every file to the GitHub repository ROOT (not in a subfolder); ensure index.html, inventory-data.json, .nojekyll and images/ are all present. Wait until the full inventory JSON loads before interacting. Use a hard refresh after GitHub Pages finishes publishing.

Back up changes: use the app's Export JSON after editing. Browser changes are saved in IndexedDB for this site and browser, and are not automatically committed to GitHub. To put later changes into a future ZIP, upload that fresh exported JSON.

v22.0 storage uses a new IndexedDB namespace: LifeTrackerInventory_v22_0. Older browser saves from v21.0 cannot overwrite the newly exported baseline.
The first load downloads and parses a large ~74 MB JSON containing inline images, so initial loading may still take time on a slower connection or device.

QA-v22.0-results.txt lists the release checks run and their results.
