# Raphaël Anselin — Portfolio

**Business analysis · Data · Applied AI**

[Visit the portfolio](https://raphoc-hub.github.io/) · [GitHub profile](https://github.com/raphoc-hub) · [LinkedIn](https://www.linkedin.com/in/raphaëlanselin)

A technical, monochrome portfolio connecting business problems to usable products. Includes a public financial-filings case study, a high-level AI knowledge architecture overview, and previews of LifeDesk and VERO.

## Implementation

Semantic HTML and responsive CSS. Self-hosted fonts and images. No runtime JavaScript, analytics, forms, tracking cookies, remote embeds or build step.

```sh
git clone https://github.com/raphoc-hub/raphoc-hub.github.io.git
cd raphoc-hub.github.io
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`. Serve over HTTP: asset paths start at the domain root.

## Project structure

- `index.html` — selected work, background and contact links.
- `work/financial-filings/` — public financial-data case study.
- `work/shared-ai-knowledge/` — conceptual AI integration case study.
- `assets/` — shared stylesheet, real public product previews, fonts and social preview.
- `404.html`, `sitemap.xml`, `robots.txt`, `.nojekyll` — static hosting support.

## Scope

This repository contains the portfolio presentation only, not private project implementations, internal research, prompts, credentials or knowledge-base contents. Dataset totals represent coverage, not adoption or financial performance. Product status is described on each page.

## Assets

Product images are screenshots of the existing public sites, captured September 2026. Geist and Geist Mono are bundled under the SIL Open Font License; notices are preserved in `assets/fonts/`. The social image is an original typographic composition.

## Quality checks

Before publication, the site was checked in Chromium and WebKit at desktop and mobile widths, without JavaScript, and with automated WCAG accessibility checks. Release tooling and private review records are maintained separately from this public export.
