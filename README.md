# Trackly PWA — Setup Guide

## Files in this package
- `index.html` — Main app
- `manifest.json` — PWA manifest
- `sw.js` — Service worker (offline support)
- `icon-192.png` — App icon (192×192)
- `icon-512.png` — App icon (512×512)

## How to run locally
Serve the folder with any static server, for example:

```bash
# Python
python3 -m http.server 8080

# Node (npx)
npx serve .
```

Then open http://localhost:8080 in Chrome/Safari.

## Install as PWA (Android / iOS)
1. Open in Chrome (Android) or Safari (iOS)
2. Tap the browser menu → **"Add to Home Screen"**
3. Tap **Add** — Trackly appears on your home screen like a native app!

## Features
- ✅ Add & remove habits
- 🌅/🌙/⚡ Morning, Evening, or Anytime tags
- 🎨 6 colour themes per habit
- 🔥 Streak tracking
- 📅 7-day week view
- 💾 All data saved locally (localStorage)
- 📴 Works offline via service worker
