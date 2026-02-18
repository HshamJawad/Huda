# جمع أسعار الطلب — Price Collector PWA

A Progressive Web App for collecting and summing order prices, built with a clean Arabic-first interface.

## ✨ Features

- **PWA Ready** — Install on iOS, Android, or Desktop directly from the browser
- **Offline Support** — Works without internet connection after first visit
- **Local Storage** — Data saved automatically on your device
- **Export / Import** — Save and load data as JSON files
- **Arabic RTL** — Fully right-to-left layout with Arabic numerals

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload all files (keep folder structure intact):
   ```
   index.html
   manifest.json
   sw.js
   icons/
     icon-72x72.png
     icon-96x96.png
     icon-128x128.png
     icon-144x144.png
     icon-152x152.png
     icon-192x192.png
     icon-384x384.png
     icon-512x512.png
   ```
3. Go to **Settings → Pages**
4. Set source to **main branch / root**
5. Your app will be live at `https://your-username.github.io/your-repo/`

> **Important:** PWA features (install prompt, offline mode) require HTTPS. GitHub Pages provides this automatically.

## 📱 Install as App

- **Android / Chrome:** Tap the menu → "Add to Home Screen"
- **iOS / Safari:** Tap Share → "Add to Home Screen"  
- **Desktop Chrome/Edge:** Click the install icon in the address bar

## 🛠 Tech Stack

- Vanilla HTML / CSS / JavaScript (no build step needed)
- Web App Manifest
- Service Worker (Cache-first strategy)
- Google Fonts: IBM Plex Sans Arabic + DM Mono
