QLOG PRO ULTIMATE V6 - GITHUB PAGES FRONTEND

UPLOAD ALL CONTENTS OF THIS FOLDER to the root of your GitHub Pages repository.
The frontend is already configured for:
  https://qlog-upgraded.mdmsportal.uk

Architecture:
  PWA (GitHub Pages / installed phone/laptop/iOS)
       -> HTTPS + Socket.IO
  qlog-upgraded.mdmsportal.uk
       -> Cloudflare qlog-api tunnel
  127.0.0.1:7000 on server PC
       -> Node.js + Socket.IO + SQLite

Do NOT upload backend files, SQLite DB, uploads, logs, or tunnel token to GitHub.
Teachers are detected from Client Inventory categories TEACHING, TEACHER, TEACHING PERSONNEL, or FACULTY.
Teacher selectors are searchable by name or ID.
All connected PWA clients receive live Socket.IO updates; manual Refresh buttons are not required.
