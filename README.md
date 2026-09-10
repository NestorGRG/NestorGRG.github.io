# Néstor García-Romeral - Personal Website

My personal academic website, built with Bootstrap 5 and the iPortfolio template.

🔗 **Live site:** [https://nestorgrg.github.io](https://nestorgrg.github.io)

## Features

- Responsive design with sidebar navigation
- About section with profile and bio
- Resume/CV section with education and experience
- Projects portfolio with filtering
- Funding section
- News section
- Contact information
- Separate pages for Papers, Posters, and Talks
- CV download in English, Spanish, and Catalan

## Structure

```
├── index.html          # Main single-page site
├── papers.html         # Papers subpage
├── posters.html        # Posters subpage
├── talks.html          # Talks subpage
├── assets/
│   ├── css/style.css   # Custom styles
│   ├── js/main.js      # Custom JavaScript
│   ├── img/            # Images
│   ├── pdf/            # CV files
│   ├── papers/         # Paper PDFs
│   ├── posters/        # Poster PDFs
│   └── talks/          # Talk slides
└── vendor/             # Third-party libraries (CDN)
```

## Color Palette

- Primary: Navy blue (#0b1d3a)
- Secondary: Steel blue (#1e3a5f)
- Accent: Teal/Cyan (#00b4d8)
- Dark: Near-black (#111827)
- Light: Silver gray (#f0f2f5)

## How to Add Content

### Papers
1. Add PDF to `assets/papers/paper-name/`
2. Add thumbnail image to same folder
3. Edit `papers.html` and add a new card entry

### Posters
1. Add PDF to `assets/posters/poster-name/`
2. Add thumbnail image to same folder
3. Edit `posters.html` and add a new card entry

### Talks
1. Add PDF (exported from PPTX) to `assets/talks/talk-name/`
2. Add thumbnail image to same folder
3. Edit `talks.html` and add a new card entry

## Deployment

This site is designed to be deployed via GitHub Pages:

1. Push to `NestorGRG/NestorGRG.github.io` repository
2. Enable GitHub Pages in repository settings
3. The site will be live at `https://nestorgrg.github.io`

## Credits

- Template: [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/) by BootstrapMade
- Libraries: Bootstrap 5, AOS, GLightbox, Swiper, PureCounter, Typed.js
