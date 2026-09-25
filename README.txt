BIKE TRACKER PWA - SETUP

Files:
- index.html       Your original Bike Tracker, with only PWA metadata + service-worker registration added.
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

IMPORTANT:
A PWA normally must be served from HTTPS (or localhost) for installation and service workers.
Do not simply open index.html with file:// and expect the Install App feature to work.

Easy deployment:
1. Upload this folder to an HTTPS static host.
2. Open the hosted page on Android Chrome.
3. Use Chrome's menu and choose "Add to Home screen" / "Install app".
4. Launch Bike Tracker from the new home-screen icon.

Your existing localStorage data stays in the browser/origin where you use the app.
If you move from a local file to a hosted PWA, use the app's Backup feature before moving/importing data.

The app's existing Google Calendar reminder links and GPS functionality are retained.
