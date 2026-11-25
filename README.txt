TRADE JOURNAL - standalone iPhone app
=====================================
Separate from your Google Sheet and Claude dashboard. Nothing here reads or writes them.

1) Put it online (free, GitHub Pages)
   - On github.com create a NEW public repo, e.g. "trade-journal-app".
   - Upload all files in this folder (index.html, manifest.json, sw.js, icon-*.png).
   - Repo Settings > Pages > Source: "Deploy from a branch", Branch: main, / (root) > Save.
   - After ~1 minute your app is at https://hafezban81.github.io/trade-journal-app/

2) Install on iPhone
   - Open that link in SAFARI > Share > Add to Home Screen.
   - Open the app from the Home Screen icon (it runs full screen, works offline).

3) Load your existing trades
   - Save starter-trades.csv to your iPhone Files (e.g. AirDrop / iCloud Drive).
   - In the app: Backup tab > Import from Google Sheet > Choose CSV file.
   - Trades 1-2 come in as "not counted" (cent account).
   IMPORTANT: import inside the installed Home Screen app, not in Safari -
   iPhone keeps their data separate.

4) Backups
   - Data lives only on your phone. Backup tab > Save backup (with photos) > Save to Files.
   - Restore the same way if you change phone or reinstall.

Updating the app later: upload the new files to the repo and change VERSION in sw.js.
