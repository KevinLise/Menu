# Sashi & Kent – Restaurant Landing Page

A responsive landing page for **Sashi & Kent**, a fine Japanese cuisine restaurant offering omakase experiences, chef's table nights, sake pairings and sushi masterclasses.

## Description

Single-page frontend built with semantic HTML5 and CSS3. Dark, elegant design with gold tones reflecting the restaurant's premium identity. Fully responsive: mobile (hamburger menu), tablet and desktop layouts via media queries.

## Technologies Used

- HTML5 (semantic tags: `header`, `main`, `section`, `article`, `nav`, `footer`)
- CSS3 (custom properties, Flexbox, Grid, media queries, transitions, keyframe animations)
- JavaScript (hamburger menu toggle)
- Google Fonts: Cormorant Garamond + Lato
- Font Awesome 6 (social media icons)

## Project Structure

```
sashi-kent/
├── index.html
├── style.css
├── script.js
├── README.md
└── img/
    ├── logo.png
    ├── fondo2.jpg
    └── fondo_1.jpg
```

## Sections

| Section | Tag used |
|---|---|
| Navigation | `<header>` + `<nav>` |
| Hero | `<section class="hero">` |
| Events & Schedule | `<section class="events">` + `<table>` with `<thead>` / `<tbody>` |
| About Us | `<section class="about">` + `<article>` |
| Gallery | `<section class="multimedia">` + CSS Grid |
| Sponsors | `<ul>` + `<li>` |
| Contact & Social | `<footer>` |

## Responsive Design

| Breakpoint | Layout |
|---|---|
| Desktop `> 1024px` | 2-column About, 4-column Gallery, full nav |
| Tablet `≤ 1024px` | 1-column About, 2-column Gallery |
| Mobile `≤ 768px` | Hamburger menu, stacked layout |
| Small mobile `≤ 480px` | Single column, adjusted typography |

## How to Run Locally

1. Download all files keeping the same folder structure
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge)

```bash
# Optional: run a local server
npx serve .
```

> **Note:** YouTube embeds require a live server to display correctly.  
> Opening via `file://` will show Error 153 — use `npx serve .` or VS Code Live Server.
