SUDARSHAN DOKE — PORTFOLIO WEBSITE

FILES
- index.html: website structure and content
- styles.css: responsive visual design, glassmorphism, effects, animations
- script.js: theme toggle, navigation, skill filters, project modals, copy actions, education scrolling
- assets/Sudarshan_Doke_CV.pdf: résumé download linked from the website

HOW TO PREVIEW
1. Extract the folder if you received it as a ZIP.
2. Open index.html in a modern browser.
3. For best clipboard behavior and more realistic deployment testing, you may run a local web server from this folder:
   python -m http.server 8000
   Then open http://localhost:8000

CUSTOMIZE BEFORE PUBLISHING
- Verify the email address and phone number in index.html.
- The social profile URL was not available in the supplied CV, so add a LinkedIn/GitHub link to the header or contact area if desired.
- Review all experience and skills and adjust anything you do not want publicly listed.
- Replace the résumé PDF in assets/ if you update your CV; keep the same filename or update the link in index.html.

DEPLOYMENT
This is a static website. Upload the folder contents to GitHub Pages, Netlify, Vercel, or any static web host. No build step or framework is required. The Google Fonts import uses an internet connection; the site remains usable if the font service is unavailable, with system-font fallbacks.

COMMAND SAFETY
The optional Python command above only starts a local static file server from the current folder. It is safe for local preview; do not expose the server to an untrusted network unless you understand the implications.
