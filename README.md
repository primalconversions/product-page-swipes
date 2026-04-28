# Product Page Swipe File

Full-page clones of 3 product pages for reference when writing new product pages for clients.

**Live site:** https://primalconversions.github.io/product-page-swipes/

## How to use

Each folder under `swipes/` contains:
- `index.html` — self-contained page (HTML + CSS + images embedded via `monolith`). Click the **view** link below to see it rendered via GitHub Pages, or feed the raw file to an AI for analysis.
- `source.txt` — the original URL.

Paste the raw `index.html` content (or a link to it) into a Claude conversation when drafting a new product page — the AI can reference hook structure, pacing, proof elements, CTAs, and visual layout.

## Regenerating / adding new swipes

```bash
brew install monolith
# Add URLs to urls.txt, then:
python3 clone.py
python3 build_readme.py
```

## Live swipes (3)

Click **view** to open the rendered page, **raw** to download the file, or **source** to open the original URL.

- `mynutraessence__pages-pms` (26.3 MB) — [view](https://primalconversions.github.io/product-page-swipes/swipes/mynutraessence__pages-pms/index.html) · [raw](https://raw.githubusercontent.com/primalconversions/product-page-swipes/main/swipes/mynutraessence__pages-pms/index.html) · [source](https://mynutraessence.com/pages/pms)
- `jshealthvitamins__products-scalp-serum` (29.1 MB) — [view](https://primalconversions.github.io/product-page-swipes/swipes/jshealthvitamins__products-scalp-serum/index.html) · [raw](https://raw.githubusercontent.com/primalconversions/product-page-swipes/main/swipes/jshealthvitamins__products-scalp-serum/index.html) · [source](https://jshealthvitamins.com/products/scalp-serum)
- `primalviking__products-primal-viking-unleashed-rital` (51.7 MB) — [view](https://primalconversions.github.io/product-page-swipes/swipes/primalviking__products-primal-viking-unleashed-rital/index.html) · [raw](https://raw.githubusercontent.com/primalconversions/product-page-swipes/main/swipes/primalviking__products-primal-viking-unleashed-rital/index.html) · [source](https://primalviking.com/products/primal-viking-unleashed-rital?view=ritual-template)
