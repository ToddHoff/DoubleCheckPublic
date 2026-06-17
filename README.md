# Double Check — public site & policies

The website and hosted policy pages for the Double Check Chrome extension.
Plain static HTML — no JavaScript, no tracking. The `.md` files are the
canonical policy texts (linked from inside the extension); the `.html`
pages are the rendered website versions. Source of truth for the `.md`
files is `docs/` in the private repo — keep them in sync.

## Live site

https://doublecheck.possibility.com/ — GitHub Pages from `main` / root,
custom domain via a Cloudflare CNAME to `toddhoff.github.io` (done June
2026; the CNAME file in this repo is what tells GitHub about the domain).

## After the store listing goes live

1. ~~Replace `CHROME_STORE_URL_TODO` in `index.html`~~ — done June 2026; the
   CTAs link to https://chromewebstore.google.com/detail/double-check/mnkfkinaakgknifodgbcakgflnaelhpe.
2. Verified-publisher badge: verify the domain in Google Search Console,
   then set it as the verified website in the Chrome Web Store dashboard.
