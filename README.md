# 3D Glass Website Demo

A visually striking portfolio-style demo website built around a **3D glassmorphism aesthetic**, with a live Three.js 3D canvas background, frosted-glass UI cards, and smooth modern styling. Originally presented as a UX/UI engineer and AI builder portfolio demo by its author.

## Features

- **3D animated background** — real-time Three.js scene rendered behind the page content.
- **Glassmorphism UI** — frosted-glass cards, blurred panels, and layered translucent sections.
- **Responsive layout** — works on desktop and mobile viewports.
- **Modern typography** — Outfit font family with a clean dark theme (`#0f172a` base).
- **Icon set** — Font Awesome 6 icons throughout the UI.
- **Utility-first styling** — Tailwind CSS via CDN, no build step required.

## Tech Stack

- HTML5, CSS3, JavaScript (vanilla)
- Three.js (r128, CDN)
- Tailwind CSS (CDN)
- Font Awesome 6 (CDN)
- Google Fonts (Outfit)

## Quick Start

This is a fully static site — no build tools, no dependencies to install.

```bash
# 1. Clone the repo
git clone https://github.com/girishlade111/3D-Glass-website-demo.git
cd 3D-Glass-website-demo

# 2. Serve locally (any static server works), e.g.:
npx serve .

# 3. Open http://localhost:3000 in your browser
```

Alternatively, just open `index.html` directly — all libraries load from CDNs, so an internet connection is the only requirement.

## Project Structure

```
.
├── index.html   # Single-page site: markup, styles, and 3D scene logic
└── README.md
```

## Deployment

The site is deployed as a static site on **GitHub Pages**, served from the `main` branch root. Any push to `main` goes live automatically.

## Author

Built by **Girish Lade** — https://ladestack.in
