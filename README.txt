Society Konnect design prototype, static package

What it is: 15 plain HTML pages plus one shared script (support.js). No build step, no server code.

To view on your computer: open a terminal in this folder and run
   python3 -m http.server 8000
then open http://localhost:8000 in a browser. (Opening index.html by double-click may not work because browsers restrict local scripts.)

To host it: upload the whole folder to any static host. Examples:
 - Netlify: drag the folder onto app.netlify.com/drop
 - Vercel, GitHub Pages, Cloudflare Pages: point at this folder
 - Your own web server: copy the folder into the web root (nginx or Apache)
Keep every file in the same folder, and keep the name support.js.

Notes:
 - Fonts load from Google Fonts, so viewers need internet access.
 - All names, prices and dates are sample data.
 - If you want it private, put the host's password or access-control feature in front of it.
