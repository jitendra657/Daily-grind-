DAILY GRIND PWA

This folder is a ready-to-upload Progressive Web App.

FILES:
- index.html   Your Daily grind checklist
- manifest.json PWA installation metadata
- sw.js         Offline caching
- icons/        App icons

IMPORTANT:
A PWA must be hosted over HTTPS (or localhost) for service-worker/offline installation.

FREE HOSTING:
1. Create a GitHub account if you don't have one.
2. Create a new PUBLIC repository, e.g. daily-grind.
3. Upload ALL files/folders from this ZIP, preserving the icons folder.
4. In the repository, open Settings -> Pages.
5. Set deployment to "Deploy from a branch", choose main and /(root), then Save.
6. GitHub will provide a https://<username>.github.io/daily-grind/ address.
7. Open that address in Chrome on your Moto Pad and choose Install app / Add to Home screen.

The checklist uses localStorage, so daily completion is saved on the device/browser.
