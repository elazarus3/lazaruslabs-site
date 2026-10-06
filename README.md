# lazaruslabs.app — Clicksy marketing site

Static site for **Clicksy™**, the GLP-1 dose-splitting and savings tracker.

| Page | Purpose |
| --- | --- |
| `index.html` | Landing page |
| `pricing.html` | Pricing hub — every medication, its source, and how patients pay |
| `privacy.html` | Privacy policy |
| `assets/` | Clicksy brand marks |

## Deploy

Pushes to `main` deploy automatically. No build step, no dependencies — the site is
already static HTML, and `vercel.json` pins the output directory to the repo root.

Production URL: <https://lazaruslabs.app>

## Editing prices

Every figure in `pricing.html` carries its source and the date it was verified.
When you update a price, update the source **and** the "verified" date with it.

## Note

`support@lazaruslabs.app` is the single contact address for the site. It is routed by
Cloudflare Email Routing to a real inbox.
