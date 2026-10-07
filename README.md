# MSL Trading Journal V6 — PWA

This is the V6 journal converted into an installable Progressive Web App.

## Install on Android
1. Put these files on a web host that supports HTTPS.
2. Open the site in Chrome on your Samsung Galaxy A07.
3. Use Chrome's menu → **Install app** (or **Add to Home screen**).
4. Launch **MSL Journal** from the home screen.

The app includes a service worker for offline caching. Trade data remains stored locally in the browser/device.

## Important
A PWA must be served from a web origin (normally HTTPS) for reliable installation and service-worker support. Opening `index.html` directly as a local file is not equivalent to installing the PWA.
