# AGENTS.md

## Project Overview

Static personal academic website. No build system, no package manager, no tests, no linting. Pure HTML/CSS/JS served via GitHub Pages.

## Key Files

- `index.html` — main single-page site (hero, about, resume, portfolio, funding, news, contact)
- `papers.html`, `posters.html`, `talks.html` — subpages for academic output
- `news-page.html` — full news archive
- `assets/css/style.css` — all custom styles
- `assets/js/main.js` — custom JavaScript
- `assets/cv/` — CV PDFs in EN/ES/CA (also duplicated in `assets/pdf/`)
- `assets/img/` — profile photo, portfolio thumbnails, favicon

## Tech Stack

- Bootstrap 5.3.2 (via CDN)
- Libraries via CDN: AOS, GLightbox, Swiper, PureCounter, Typed.js, Isotope, Waypoints, Boxicons, Bootstrap Icons
- No local `vendor/` directory (README is stale on this)
- Contact form uses FormSubmit.co (POST to `nestorgarcia-romeral@ub.edu`)

## Deployment

Push to `NestorGRG/NestorGRG.github.io` → GitHub Pages serves at `https://nestorgarcia-romeral.github.io`

## Content Editing

When adding papers/posters/talks:
1. Add PDF + thumbnail to the corresponding folder under `assets/`
2. Add a card entry in the matching HTML file (follow existing card structure exactly)
3. Card markup uses Bootstrap grid with `data-aos` fade animations

## Gotchas

- No HTML minification or bundling — files are served as-is
- No CI/CD checks — validate HTML manually before pushing
- CV PDFs exist in both `assets/cv/` and `assets/pdf/` (index.html references `assets/cv/`)
- Footer credits iPortfolio template — do not remove BootstrapMade attribution
