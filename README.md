# STACKED — installable money dashboard

A lightweight Progressive Web App for Android and desktop. It includes editable balances, a weekly budget, savings goals, and JSON backup export.

## Preview
Open `index.html` in a browser. The main features work locally, but installation and offline caching require serving the app from `localhost` or a secure HTTPS website.

## Install on Android and PC
PWAs need a secure origin (HTTPS, or localhost). To install on both devices, publish the contents of this folder using a static hosting service such as GitHub Pages or Netlify:
1. Create an account with the hosting service.
2. Upload the four app files (`index.html`, `manifest.json`, `sw.js`, `icon.svg`) and keep their names unchanged.
3. Open the HTTPS site on Android in Chrome; use the browser menu and choose **Install app** or **Add to Home screen**.
4. Open the same site on PC in Chrome or Edge and select the install icon in the address bar, or use the browser menu → **Install STACKED**.

## Data and privacy
- Balances, budget lines and goals are saved in that browser's local storage.
- Phone and PC do not automatically sync with each other.
- Use **Export backup** to download a JSON backup.
- Avoid clearing browser site data unless you have a backup.
- Starting balances are demo values; update them to your current figures.

This is a starter PWA, not an app-store release. Installation is through a supported browser.
