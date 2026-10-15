# doingitfordoris

Doing it for Doris: static site for doingitfordoris.com, served by GitHub Pages.

- `index.html` homepage, `privacy.html` privacy notice
- `assets/fonts/` self-hosted fonts (SIL OFL, licences alongside); no Google Fonts
- Analytics: Cloudflare Web Analytics (cookieless), injected automatically by Cloudflare at the edge (RUM "Enable" setting). No snippet in the pages; the CSP allows static.cloudflareinsights.com and cloudflareinsights.com for it.
