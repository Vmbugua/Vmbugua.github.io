# My Portfolio

This is my personal portfolio site — I'm Veronicah Mbugua, a data analyst based in Nairobi, Kenya. It's a single-page site built with plain HTML, CSS, and JavaScript, no frameworks or build step.

**Live site:** https://vmbugua.github.io/

## Overview

It's a single scrollable page with a sticky nav bar that highlights the active section as you scroll. Sections:

- **Home** — intro, tagline, CV download, and a link into my Projects section
- **About** — my background, education, and a few quick facts
- **Skills** — my toolkit, grouped into data analysis, visualization, version control, statistics, and soft skills
- **Projects** — featured work with tech tags and GitHub links
- **Contact** — a working contact form plus direct links to my LinkedIn, GitHub, and email

## Tech Stack

- HTML5
- CSS3 (custom properties, CSS Grid/Flexbox, no framework)
- Vanilla JavaScript (`IntersectionObserver` for scroll effects and active-nav highlighting)
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) — Montserrat
- [Formspree](https://formspree.io/) for contact form submissions (no backend required)

## File Structure

```
├── index.html        # Single-page site (all sections)
├── style.css          # Styles: layout, palette, components, responsiveness
├── script.js           # Nav toggle, scroll reveal, active-link highlighting, form submit
└── Images/
    ├── Profile pic.png
    └── SQL pic.jpg
```

## Design

- **Palette:** white / off-white background with a teal accent (`#0d9488`) for links, buttons, and hover states
- **Typography:** Montserrat throughout
- **Responsive:** collapses to a hamburger menu below 760px; grid sections stack on smaller screens
- Respects `prefers-reduced-motion` for anyone who has animations turned off

## Running Locally

No build tools needed — just open `index.html` in a browser, or serve the folder with any static server, e.g.:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.

## Deployment

Hosted via **GitHub Pages** directly from this repository. Any push to the default branch updates the live site.

## Contact Form Setup

The form posts to Formspree (`https://formspree.io/f/xqerdzeo`) and submits via `fetch` so the page doesn't reload. To point it at a different Formspree endpoint (or your own), update the `action` attribute on the `<form id="contact-form">` element in `index.html`.

## To Do

- [ ] Add real content and screenshots for my three "coming soon" project cards
- [ ] Link my actual CV file (`Veronicah_Mbugua_CV.docx`) in the Home section

## Contact Me

- GitHub: [@Vmbugua](https://github.com/Vmbugua)
- LinkedIn: [veronicah-mbugua](https://www.linkedin.com/in/veronicah-mbugua-54a743422)
- Email: mbuguaveronicah01@gmail.com
