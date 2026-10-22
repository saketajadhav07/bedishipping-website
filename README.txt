BEDISHIPPING PVT LTD WEBSITE
============================

This is a static HTML/CSS/JS website designed for Cloudflare Pages.

FILES
-----
index.html
about.html
services.html
seafarers.html
shipowners.html
contact.html
css/style.css
js/script.js

DEPLOYMENT
----------
1. Create a GitHub repository named bedishipping-website.
2. Upload the contents of this folder so index.html is in the repository root.
3. In Cloudflare Dashboard, go to Workers & Pages > Create application > Pages > Import an existing Git repository.
4. Select the GitHub repository.
5. Production branch: main
6. Build command: exit 0
7. Build output directory: /
8. Deploy.
9. Add bedishipping.com under Custom domains.

IMPORTANT
---------
The contact form currently uses the visitor's email client via mailto. For a true website contact form that sends automatically, connect a form service or a Cloudflare Pages Function later.

The website uses remote Unsplash imagery in the hero section. Replace with licensed company imagery before final production if desired.
