# HOPPP! Landing Page

Landing page for [HOPPP!](https://hoppp.kobar.co) — hosted on Cloudflare Pages.

## Structure

```
index.html            # Main landing page (single-page)
privacy-policy.html   # Privacy Policy (standalone, dedicated URL)
terms-of-use.html     # Terms of Use (standalone, dedicated URL)
```

## Legal Pages

Privacy Policy and Terms of Use live as standalone HTML files with dedicated URLs:

- `https://hoppp.kobar.co/privacy-policy.html`
- `https://hoppp.kobar.co/terms-of-use.html`

These are the single source of truth for legal content. The main `index.html` links to them from the footer. Play Store requires direct URLs that render without JavaScript — these pages are static HTML.

**To update legal content**, edit the dedicated HTML file directly. No duplication exists elsewhere.

## Deployment

Push to `main` branch. Cloudflare Pages auto-deploys.
