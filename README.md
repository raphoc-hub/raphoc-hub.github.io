# Raphaël Anselin — Portfolio

**Business analysis · Data · Applied AI · Digital marketing**

[Visit the portfolio](https://raphoc-hub.github.io/) · [GitHub profile](https://github.com/raphoc-hub) · [LinkedIn](https://www.linkedin.com/in/raphaëlanselin)

A technical, monochrome portfolio connecting business problems to usable products. Includes a public financial-filings case study, a high-level AI knowledge architecture overview, previews of LifeDesk and the official VERO storefront, and two playable VERO advertising/brand films.

## Implementation

Semantic HTML and responsive CSS. Self-hosted fonts, images and video. No runtime JavaScript, analytics, forms, tracking cookies, remote embeds or build step.

```sh
git clone https://github.com/raphoc-hub/raphoc-hub.github.io.git
cd raphoc-hub.github.io
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`. Serve over HTTP: asset paths start at the domain root. This simple Python server previews the pages, but video seeking requires a static server with HTTP byte-range support. The live GitHub Pages deployment supports byte-range requests.

## Project structure

- `index.html` — selected work, background and contact links.
- `work/financial-filings/` — public financial-data case study.
- `work/shared-ai-knowledge/` — conceptual AI integration case study.
- `#motion` — digital marketing and advertising showcase: ROOT product film (9:16) and VERO identity film (4:5).
- `assets/video/` — 720px-wide H.264 Constrained Baseline Level 3.1 playback copies with bounded bitrate, plus separate 1080p downloads, poster images and English visual-description tracks. Native controls and full-size links use the compatible copies; no autoplay or video preload.
- `assets/` — shared stylesheet, real public product previews, fonts and social preview.
- `404.html`, `sitemap.xml`, `robots.txt`, `.nojekyll` — static hosting support.

## Scope

This repository contains the portfolio presentation only, not private project implementations, internal research, prompts, credentials or knowledge-base contents. Dataset totals represent coverage, not adoption or financial performance. Product status is described on each page.

## Assets

Product images are screenshots of the existing public sites. VERO’s official storefront at https://verolab.co was captured October 2026; other previews were captured September 2026. The two VERO creative samples are shown as product-advertising and brand-storytelling work, not paid-campaign performance evidence. Video aspect ratios and frame rates are preserved; the ROOT sample is silent and the identity sample retains its original audio. Text alternatives describe the visible sequence; they are not speech transcripts. Geist and Geist Mono are bundled under the SIL Open Font License; notices are preserved in `assets/fonts/`. The social image is an original typographic composition.

## Quality checks

Before publication, the site was checked in desktop Chromium and WebKit at desktop and mobile widths, without JavaScript, and with automated WCAG accessibility checks. Touch and constrained-network checks use desktop Chrome mobile emulation; these do not establish physical Android-device compatibility. Media-profile regressions enforce Baseline Level 3.1 on default playback. Release tooling and private review records are maintained separately from this public export.
