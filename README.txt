ARIGUAT HF INSIGHT ASSISTANT — INSTALLABLE OFFLINE PWA

Upload ALL five files to the ROOT of your GitHub repository:
  index.html
  manifest.json
  sw.js
  icon-192.png
  icon-512.png

Then enable GitHub Pages: Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
Wait for the HTTPS site to publish. Open the published https://USERNAME.github.io/REPOSITORY/ URL
in Chrome on Android or Chrome/Edge on Windows. Open the browser menu and choose Install app
or Install and create shortcut, depending on browser/version.

IMPORTANT: Open the published HTTPS URL online at least once and allow it to finish loading so
the service worker can cache the files. Then test offline. This caches the scripted chatbot only;
it does not add generative AI. Google Fonts are not requested by this offline version, so fallback
fonts may look slightly different. The GitHub Pages site itself needs internet for first visit.
Use a public repository only if the content is approved for public sharing.
