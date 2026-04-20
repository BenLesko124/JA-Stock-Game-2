# JA Stock Market Challenge

This project is set up to upload as a static GitHub repo.

## Files

- `index.html`: the app entry file

## Publishing notes

- Keep the filename as `index.html` if you want to deploy with GitHub Pages.
- Multiplayer depends on Firebase Realtime Database and the Firebase config already embedded in the page.
- If you publish this publicly, make sure your Firebase rules and allowed origins are configured the way you want.

## What was fixed here

- Repaired JavaScript-breaking quoted titles in the game data.
- Added a safe fallback when hard-mode hint arrays are missing.
- Saved the workspace copy as UTF-8 so GitHub handles it more cleanly.
