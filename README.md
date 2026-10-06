# Eukairox

Marketing site for [eukairox.com](https://eukairox.com): AI employees leased to Ontario restaurants.

Static HTML/CSS/JS. No build step.

## Structure

- `index.html` – homepage (hero, stat band, AI team, ROI calculator, pricing, FAQ, contact form)
- `services/`, `industries/`, `blog/` – supporting pages
- `privacy.html`, `terms.html` – legal
- `sitemap.xml`, `robots.txt`, `llms.txt` – SEO
- `vercel.json` – clean URLs, no trailing slash

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Hosted on Vercel (project `eukairox`). Connecting this repo to the Vercel project gives automatic deploys on every push to `main`.

## Design tokens

- Font: Hanken Grotesk
- Surfaces: `#FFFFFF`, `#F5F5F7`, `#000000`
- Ink: `#1D1D1F`, secondary `#6E6E73`, tertiary `#86868B`
- Accent blue: `#0071E3` (hover `#0058B8`), on dark `#2997FF`
- Money green: `#1D8F4E`, on dark `#4CD787`
