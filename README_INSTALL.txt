# DFW Concierge Bookings — iPhone Install App

This package turns your booking page into an installable iPhone web app.

## What is included
- `index.html` — your booking app
- `manifest.webmanifest` — app name, icon, and standalone mode
- `service-worker.js` — offline caching
- `icons/` — iPhone and PWA icons

## Install on iPhone
1. Upload this folder to any HTTPS host, such as Netlify, Vercel, GitHub Pages, or your website hosting.
2. Open the hosted link in Safari on your iPhone.
3. Tap the Share button.
4. Tap “Add to Home Screen.”
5. Tap “Add.”

The app will appear on your iPhone Home Screen like a normal app.

## Important note
Your bookings are saved in the phone/browser local storage. They stay on that device only. If you delete Safari data or change phones, the bookings may not transfer unless you add cloud/database storage later.
