# timjon.es

The personal site of **Tim Jones** — part CV, part portfolio, all me.

**[timjon.es](https://timjon.es)** is where I introduce myself to the world: who I am,
what I've worked on, and how to get in touch.

## About me

I'm a software builder based in San Francisco, currently at
[Keepsafe](https://github.com/KeepSafe). This site is my home on the web — a
place to put a face to the name before you meet me, or after.

## What's here

This repository holds the source for the site — a single-page portfolio with:

- **Hero** — who I am, with an orbiting-rings portrait and a rolling ticker
- **About** — background and quick facts
- **The Lab** — side projects I've built for fun
- **Track record** — growth, by the numbers
- **Journey** — the career timeline, from art director to head of product
- **Contact** — how to reach me

## Stack

No frameworks, no build step — just static files:

- `index.html` — all content and markup
- `css/style.css` — styles, animations, and mobile-responsive breakpoints
- `js/main.js` — a live Boulder clock and the mobile nav toggle
- `images/` — optimized portrait (WebP + JPEG fallback) and favicon

Fonts (Archivo + Space Mono) load from Google Fonts. The layout is
mobile-optimized with breakpoints at 960px, 820px, 640px, and 560px, and
respects `prefers-reduced-motion`.

## Development

```
git clone https://github.com/j1mtones/timjone.es.git
cd timjone.es
python3 -m http.server   # then open http://localhost:8000
```

There's nothing to install or compile — edit the files and refresh.

## Get in touch

- 🌐 [timjon.es](https://timjon.es)
- 🐙 [@j1mtones](https://github.com/j1mtones) on GitHub
- ✉️ tim.b.jones@gmail.com
