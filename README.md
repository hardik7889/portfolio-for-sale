# Rahul Sharma — Portfolio (For Sale)

A premium personal portfolio website: holographic 3D "Holo Prism" design,
single self-contained HTML file, no build step, no dependencies.

**Live:** https://hardik7889.github.io/portfolio/

## Sections

Hero · About · Skills · Experience · Education · Projects · Achievements · Contact

## Features

- Holographic portrait orb — rotating orbit rings, glow disc, travelling node
- Grayscale → colour portrait wake-up on hover
- Mouse-driven 3D tilt on portrait and project cards
- Multi-colour hover gradient + neon halo on every text element
- Typewriter role line with blinking caret
- Scroll reveals with animated heading underlines
- Infinite CSS skills marquee
- Responsive — collapses to one column under 860px

## Structure

```
index.html                 the live site (Holo Prism)
assets/portrait_cut.webp   optimised portrait (primary)
assets/portrait_cut.png    original cutout (source for edits)
designs/                   6 alternative themes — v1..v6, each standalone
```

## Running locally

No tooling needed — open `index.html` in a browser, or:

```bash
python -m http.server 8000
```

## Deployment

Static — GitHub Pages, Netlify, or Vercel. Upload `index.html` + `assets/`.

## License

Personal project — all rights reserved.
