ST.LAWRENCE AND MARGARITA DOSAL SCHOOL ORPHANAGE — PWA
=======================================================

FILES
-----
index.html      Main site (PWA-enabled)
style.css       Site styles
script.js       Site interactions
manifest.json   App identity (name, icons, colors)
sw.js           Service Worker for offline support
icons/          App icons (192px + 512px)

HOSTING
-------
Option A – GitHub Pages:
  1. Create repo, upload all files keeping folder structure
  2. Settings → Pages → Deploy from main branch
  3. URL: https://USERNAME.github.io/REPO/

Option B – Netlify (drag & drop):
  1. netlify.com → "Deploy manually"
  2. Drag the orphanage-pwa folder onto the page

Option C – Any web server: upload as-is over HTTPS.

INSTALL ON DEVICES
------------------
Android (Chrome):  visit URL → "Add to Home Screen" banner
iPhone (Safari):   Share → "Add to Home Screen"
Desktop (Chrome):  install icon in address bar

NOTES
-----
• HTTPS is required for PWA install/offline support
• Works offline after first visit (cached by sw.js)
• To replace the AGAPE icon with your own, swap icons/icon-192.png and icon-512.png
