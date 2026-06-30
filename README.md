# Somnia — A Dream Archive

An immersive, scroll-driven 3D website that simulates walking through someone's archive of dreams. Each "fragment" is a fully realized 3D scene — floating crystals, melting clocks, an infinite mirror corridor, and blooming flowers — woven together with cinematic scroll transitions, ambient procedural audio, and a custom cursor experience.

## Inspiration

The idea came from the feeling of half-remembering a dream right after waking up — fragmented, beautiful, slightly uncanny. Rather than building a single 3D scene, Somnia is structured as four distinct "rooms," each representing a different sensation dreams can carry: suspension (crystals), distortion (clocks), self-reflection (mirrors), and renewal (bloom).

## Technologies & Tools Used

- **Three.js (r128)** — all 3D scenes, lighting, geometry, and per-room WebGL renderers
- **GSAP + ScrollTrigger** — scroll-driven reveal animations and timeline sequencing
- **Web Audio API** — fully procedural ambient soundscape (oscillator drones, LFO vibrato, filtered noise) — no external audio files
- **Vanilla JavaScript** — custom cursor, parallax mouse tracking, navigation, loading sequence
- **HTML5 / CSS3** — typography (Cormorant Garamond + Raleway via Google Fonts), layout, responsive design

No frameworks, no build step — a single self-contained HTML file.

## Features

- Custom animated loading screen
- Four distinct 3D "dream rooms," each with independent Three.js scenes and lighting
- Procedurally generated ambient audio (toggleable, zero external audio assets)
- Mouse-reactive parallax on typography and camera movement
- Scroll-triggered reveal choreography (GSAP ScrollTrigger)
- Hidden "Deep Dream" mode (click the logo)
- Fully responsive (mobile breakpoints included)

## Running locally

This is a static single-file site — just open `index.html` in a browser, or serve the folder with any static file server.

```bash
npx serve .
```

## Author

Built solo for the 3D Websites Hackathon.
