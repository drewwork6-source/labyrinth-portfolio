# Labyrinth Portfolio

**🔗 Live:** https://drewwork6-source.github.io/labyrinth-portfolio/

An interactive, scroll-driven 3D portfolio site. You walk through a maze rendered in Three.js — colored beacons and drifting dust mark each turn — before falling down a hole at the end, bouncing, and settling into a lamp-lit moment where a final contact card fades in.

## Experience

- **The walk** — scroll to move down a winding corridor built from a `CatmullRomCurve3` camera path. Jewel-toned beacons (light + orb + halo + glow pillar + floor pool) mark each turn, with colorful dust drifting through the whole maze.
- **The panels** — six scroll-revealed text panels along the way: an intro, an about-me section, a projects list, a skills grid, a "the walls just ended" beat, and a final contact card.
- **The fall** — at the end of the corridor, the walk gives way to a straight drop, a bounce, and a settle where a lamp turns on and the camera levels out to reveal the final contact bubble.

## Tech Stack

- **Three.js** (r160, classic global build) — no build step, works straight from a static file server
- Vanilla HTML/CSS/JS — virtual-scroll-driven camera and panel system, no framework

## Running Locally

```bash
open index.html
# or
python -m http.server 8000
```

## Status

🟢 Live, hosted via GitHub Pages from the `main` branch.
