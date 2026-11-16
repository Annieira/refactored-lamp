# DAILY DOSE — Android-ready web app

A free, installable Progressive Web App (PWA) starter for Android.

## Files
- `index.html` — the app
- `manifest.webmanifest` — app name, icon and install settings
- `sw.js` — offline cache
- `icons/` — app icons

## Publish for free
1. Create a free GitHub account at https://github.com/ if you don't have one.
2. Create a new **public** repository named `daily-dose`.
3. Upload every file and folder from this project. Keep the folder structure.
4. In Netlify, sign up for the free plan at https://www.netlify.com/ and choose **Add new project / Import an existing project**.
5. Connect GitHub, select `daily-dose`, and deploy. No build command is needed; publish directory is `.`.
6. Open the HTTPS website on your Android phone in Chrome.
7. Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.

## Test locally
A PWA install prompt and service worker require HTTPS or localhost. Opening `index.html` directly from Files is fine for a quick preview, but use the deployed HTTPS URL for installation/offline support.

## Notes
- Favourites are saved locally in that browser/device using local storage.
- The daily quote changes by calendar date.
- This starter does not yet send notifications or sync favourites between devices.
- No paid API, database, or backend is required for this first version.
