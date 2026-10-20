FORGE V3 - COMPLETE GITHUB PAGES APP

This folder contains the entire app, not a patch.

FILES:
- index.html (app and training program)
- sw.js (offline cache)
- manifest.webmanifest (home-screen app settings)
- icon.svg (app icon)

GITHUB PAGES SETUP:
1. Create a public GitHub repository named FORGE.
2. On the repository main page choose Add file > Upload files.
3. Upload the FOUR app files listed above to the ROOT of the repository (not a subfolder, and not the ZIP itself). README.txt is optional.
4. Commit changes.
5. Open Settings > Pages > Build and deployment > Deploy from a branch.
6. Choose main and /(root), then Save.
7. Open https://YOUR-USERNAME.github.io/FORGE/ once GitHub Pages has finished deploying.

UPDATING:
Export a backup from the old FORGE app first. Replace all four files in the repository root and commit. If the old version is still shown, close and reopen the app, then refresh; service worker caching can delay updates.

DATA:
Workout logs are saved locally in the browser on each device, not synced by GitHub. Export backups regularly. Clearing browser storage can erase records.
