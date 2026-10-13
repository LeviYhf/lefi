# Goldline Daily Hub

This folder contains the complete static web app and its install/offline-support files.

## Files
- `index.html` — main entry point for GitHub Pages and browser use
- `goldline_daily_hub.html` — same app under the descriptive filename used in the GitHub repository
- `manifest.webmanifest` — installable web app metadata
- `sw.js` — service worker for basic offline caching
- `icon-192.png` and `icon-512.png` — app icons

## Run locally
Open `index.html` in a modern browser. Some install/service-worker features require HTTPS or localhost.

## Publish on GitHub Pages
Upload the files in this folder to the root of the repository, then go to **Settings → Pages** and enable deployment from the `main` branch and `/ (root)`. Open the published Pages URL. `index.html` is the default page.

## Notes
- User data is saved in that browser's local storage and does not automatically sync across devices.
- Schoology/PowerSchool integration and external sports-calendar feed syncing are not implemented in this standalone build.
- External CDN fonts, icons, and Tailwind CSS require an internet connection.
