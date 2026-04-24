# Deyber Hernández González — Portfolio

Personal portfolio website for Deyber Hernández González, Systems Engineer and cybersecurity professional from Costa Rica.

**Live site:** [deyber13013.github.io](https://deyber13013.github.io)

---

## About

Single-page portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step. Served directly via GitHub Pages.

**Sections:**
- Hero / introduction
- About me
- Work experience
- Education
- Skills
- Projects
- Certifications & badges
- Research / publications
- Contact

## Features

- **Bilingual (ES / EN)** — custom i18n system with automatic browser language detection and manual toggle
- **Dark mode design** — CSS custom properties, gradient background, teal/blue accent palette
- **Responsive** — flexbox/grid layout with mobile breakpoints at 920px and 580px
- **Scroll animations** — `IntersectionObserver` fade-in for section elements
- **Matrix rain canvas** — subtle cybersecurity-themed background effect
- **Zero dependencies** — only external resource is Google Fonts

## Tech stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styles | CSS3 (custom properties, grid, flexbox) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Syne, DM Sans, DM Mono |
| Hosting | GitHub Pages |

## Local development

No build process required. Clone and open in browser:

```bash
git clone https://github.com/Deyber13013/Deyber13013.github.io.git
cd Deyber13013.github.io
open index.html   # or use any static server
```

For live reload during development, any static server works:

```bash
# Python
python3 -m http.server 8080

# Node (npx)
npx serve .
```

## Deployment

Every push to `main` is automatically deployed by GitHub Pages. No action required.

## Project structure

```
.
└── index.html   # entire application (HTML + inline CSS + inline JS)
```

## Contact

- Email: deihg13@hotmail.com
- LinkedIn: [linkedin.com/in/deyber13013](https://www.linkedin.com/in/deyber13013)
- GitHub: [github.com/Deyber13013](https://github.com/Deyber13013)
