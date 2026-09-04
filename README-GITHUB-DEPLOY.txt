QLOG PRO - GITHUB PAGES FRONTEND
================================

THIS FOLDER IS THE ONLY CONTENT TO UPLOAD TO GITHUB.

Already configured API backend:
  https://qlog-upgraded.mdmsportal.uk

GitHub upload:
  Upload ALL files and folders INSIDE this FRONTEND-GITHUB-PAGES folder
  to the ROOT of your GitHub repository.

Required root files:
  index.html
  config.js
  manifest.json
  service-worker.js
  .nojekyll
  fonts/
  icons/
  libs/
  models/

DO NOT upload backend files, SQLite databases, uploaded certificates/eIPCRFs,
or Cloudflare tunnel tokens to GitHub.

GitHub Pages:
  Repository -> Settings -> Pages
  Deploy from a branch -> main -> /(root) -> Save

The frontend remains installable/offline-first for its static app resources.
Live SQLite synchronization and certificate/eIPCRF uploads require the backend
tunnel to be online.

If the backend hostname changes later, edit only config.js.
