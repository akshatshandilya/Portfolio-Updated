Akshat Shandilya - Portfolio
============================

Files
- index.html                                 The complete portfolio (HTML, CSS, JS, profile photo and resume are embedded).
- favicon.svg, favicon.ico,                  Browser-tab icon (AS monogram) and iPhone home-screen icon.
  favicon-32x32.png, favicon-16x16.png,      Keep these in the same folder as index.html.
  apple-touch-icon.png
- Akshat_Shandilya_AI_Engineer_Resume.pdf    Your resume, for your records / to upload anywhere else.

Deploy (any static host)
- Netlify / Vercel / Cloudflare Pages: drag and drop this folder, or connect a repo containing all of these files.
- GitHub Pages: push all files to a repo, then Settings > Pages > deploy from the main branch.

Notes
- The site is always in dark mode, whatever the visitor's device theme is.
- Needs internet only for Google Fonts (Manrope, Hanken Grotesk, JetBrains Mono); falls back to system fonts offline.
- The Resume button downloads the resume embedded inside index.html. If you change the resume later, the embedded copy must be updated too (ask Claude to regenerate index.html).
- Favicons can be cached by browsers for a while; if you don't see the new icon right away, hard-refresh or open the site in a private window.
