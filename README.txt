# Naina Online PWA

This folder is ready to deploy as a static website.

Files:
- index.html — Naina V5.1
- manifest.webmanifest — home-screen install metadata
- sw.js — service worker
- icons/ — Naina app icons

Recommended deployment:
1. Upload all files/folders in this directory to any HTTPS static hosting service.
2. Open the resulting HTTPS URL in Chrome on Android.
3. Choose "Install app" / "Add to Home screen".
4. Naina will appear as an app icon.

Important:
- Naina stores timetable/tasks in the browser's local storage on each device.
- The Excel engine is loaded from jsDelivr with an unpkg fallback, so the first Excel import needs internet access.
