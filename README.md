# MicroLink Data Centers - Website

Static site. No build step. Every page is a self-contained HTML file; shared images live in /assets.

Pages: index.html, technology.html, portfolio.html, hosts.html, community.html
Support: robots.txt, sitemap.xml, _redirects (Cloudflare Pages), favicon.svg

Editing: open any .html file, change text directly. Replace images by dropping a new file
with the same name into /assets. Site data for the portfolio page lives in the SITES
array inside portfolio.html and drives all charts and cards.

Deploy: Cloudflare Pages, project microlinkdc-site. Push to main = live.
