# Mariam Khatab — Portfolio

An interactive, single-page portfolio for **Mariam Khatab**, Architecture Engineering (New Giza University) — work at the intersection of architecture, environmental computation and machine learning.

**Live site:** https://mariamkhatab.github.io/portfolio/

## Featured work

1. **ECHOANA** — a recovery residence where machine learning discovers therapeutic room profiles from patient data and drives an adaptive facade.
2. **Circadian-Responsive Hospital Room** — room geometry generated from a circadian light target to help regulate patient melatonin.
3. **Park Tech NGU** — a campus parking lot re-imagined as a sensing structure with kinetic sun-tracking louvers.

## About the build

- Single, self-contained `index.html` — no build step, no dependencies to install.
- Vanilla HTML / CSS / JavaScript.
- A day/night theme toggle (persists to `localStorage`, respects `prefers-color-scheme`).
- A scrubbable sun-arc hero, custom cursor, scroll-reveal, and interactive project widgets.
- Fully responsive across desktop and mobile.

Fonts are loaded from Google Fonts; the ECHOANA figures are served from its own project site, and the Circadian / Park Tech images live in `assets/`.

## Running locally

Because the page fetches a few assets, open it through a local server rather than the `file://` protocol:

```bash
python -m http.server 8000
# then visit http://localhost:8000/
```

## Deployment

The site is published with **GitHub Pages** from the `main` branch (root). Any push to `main` redeploys automatically.
