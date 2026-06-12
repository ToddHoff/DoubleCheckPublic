# Double Check — public site & policies

The website and hosted policy pages for the Double Check Chrome extension.
Plain static HTML — no JavaScript, no tracking. The `.md` files are the
canonical policy texts (linked from inside the extension); the `.html`
pages are the rendered website versions. Source of truth for the `.md`
files is `docs/` in the private repo — keep them in sync.

## Enable GitHub Pages (one time)

Settings → Pages → "Deploy from a branch" → branch `main`, folder `/ (root)`.
The site appears at https://toddhoff.github.io/DoubleCheckPublic/

## After the store listing goes live

Replace `CHROME_STORE_URL_TODO` (two places in `index.html`) with the real
Chrome Web Store listing URL.

## Optional: custom domain + verified-publisher badge

1. Add a DNS CNAME record: `doublecheck.possibility.com` → `toddhoff.github.io`
2. Settings → Pages → Custom domain → `doublecheck.possibility.com`
   (creates a CNAME file; keep "Enforce HTTPS" on)
3. Verify the domain in Google Search Console, then in the Chrome Web Store
   dashboard set it as the item's website — the listing gains a
   "verified publisher" badge.
