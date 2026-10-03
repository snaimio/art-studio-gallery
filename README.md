# Art & Creative Studio Portfolio

> A responsive, multi-page creative portfolio website featuring an artist biography, categorized art gallery across traditional and digital mediums, philosophy breakdown, and interactive contact form.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Pages: Multi-Page](https://img.shields.io/badge/Pages-4%20Pages-informational)](index.html)
[![Responsive Design](https://img.shields.io/badge/Design-Responsive-success)](https://web.dev/responsive-web-design-basics/)

---

## Table of Contents

- [Overview](#overview)
- [Multi-Page Architecture](#multi-page-architecture)
- [Key Features](#key-features)
- [HTML & CSS Skills Demonstrated](#html--css-skills-demonstrated)
- [Project Structure](#project-structure)
- [Responsive Breakpoints](#responsive-breakpoints)
- [Getting Started](#getting-started)
- [Author & License](#author--license)

---

## Overview

This project is a multi-page web application designed for an artist and visual designer. It showcases artwork across three distinct mediums: Traditional Painting, Digital Art & Cyberpunk, and 3D Sculptures. Built with responsive web standards, it delivers a gallery viewing experience on desktop, tablet, and mobile browsers.

---

## Multi-Page Architecture

The website comprises 4 interlinked HTML pages sharing a consistent design system and styling:

1. **Home (`index.html`)**: Artistic landing page featuring the artist statement, creative philosophy introduction, and featured artwork preview.
2. **About (`about.html`)**: Personal story, artist bio portrait, creative journey timeline, artistic philosophy cards (Emotion, Balance, Simplicity), and exhibition awards.
3. **Gallery (`gallery.html`)**: Categorized art exhibition grid containing 18 curated artwork pieces with high-resolution imagery and descriptions:
   - *Traditional Painting*: Acrylics, oils, and watercolors (`paint1.png` to `paint6.png`).
   - *Digital Art*: Neon, cyberpunk, and 3D compositions (`digital1.png` to `digital6.png`).
   - *Modern Sculpture*: Form, balance, and spatial movements (`sculpture1.png` to `sculpture6.png`).
4. **Contact (`contact.html`)**: Commission inquiry form, studio location map graphic, and social media connectivity.

---

## Key Features

- **Multi-Category Gallery**: Auto-fitting responsive grid exhibiting 18 distinct art pieces.
- **Persistent Header & Navigation**: Sticky navbar with active state indicator for current page location.
- **Custom Web Typography**: Google Fonts pairing `Stardos Stencil` with `Inter` for an artisanal yet modern editorial aesthetic.
- **Touch-Friendly Accessible Form**: Clean form layout with styled input focus states and responsive full-width mobile view.
- **Micro-Interactions**: Hover elevation, image zoom effects, and smooth color transitions.

---

## HTML & CSS Skills Demonstrated

### 1. Multi-Page Site Navigation & Semantic Markup
- Clean relative linking across subpages with dynamic `.active` navigation styling.
- Comprehensive semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- Standardized metadata and Open Graph considerations.

### 2. Modern CSS3 Layouts
- **CSS Grid Layout**: Gallery grids dynamically adapt columns using `repeat(auto-fill, minmax(320px, 1fr))`.
- **Flexbox Containers**: Symmetrical bio section layout, responsive navigation alignment, and philosophy cards.
- **CSS Variables**: Centralized styling palette with custom properties for color theming, spacing, and shadows.
- **Aspect Ratio & Object-Fit**: Uniform image presentation across varying source image proportions with `object-fit: cover`.

---

## Project Structure

```plaintext
html_assignment_2/
├── assets/
│   └── images/
│       ├── art1.png ... art3.png       # Featured hero artworks
│       ├── bioPic.png                 # Artist portrait
│       ├── digital1.png ... digital6.png # Digital art collection
│       ├── headerBkg.png              # Header hero banner background
│       ├── introBkg.png               # Section transition background
│       ├── map.png                    # Studio location map
│       ├── paint1.png ... paint6.png  # Traditional painting collection
│       ├── sculpture1.png ... sculpture6.png # Sculpture collection
│       └── social icons (dragonbit, linkedin, twitter, logo)
├── css/
│   └── app.css                        # Global responsive stylesheet
├── js/
│   └── app.js                         # Interactive scripts
├── about.html                         # Artist bio & philosophy page
├── contact.html                       # Inquiry form & contact page
├── gallery.html                       # 18-piece categorized artwork gallery
├── index.html                         # Homepage & featured showcase
├── LICENSE                            # MIT Open Source License
└── README.md                          # Documentation
```

---

## Responsive Breakpoints

| Device Category | Viewport Range | Key Adjustments |
| :--- | :--- | :--- |
| **Desktop** | `> 900px` | 3-column gallery grid, side-by-side bio layout, full navigation |
| **Tablet** | `701px - 900px` | 2-column gallery grid, vertically stacked artist bio, flexible form |
| **Mobile** | `<= 700px` | Single-column gallery cards, stacked navbar, mobile-optimized padding |

---

## Getting Started

1. Clone or download the repository:
   ```bash
   git clone https://github.com/<username>/html_assignment_2.git
   cd html_assignment_2
   ```
2. Open `index.html` in your favorite web browser.

---

## Author & License

- **Author**: Sheikh Naim
- **License**: Released under the [MIT License](LICENSE).
