# Blueprint Portfolio — Ekansh

An interactive, high-tech 3D architectural CAD blueprint portfolio website inspired by sci-fi tactical telemetry and engineering schematics.

Live Demo: [https://ekanshvijay747-svg.github.io/blueprint-portfolio/](https://ekanshvijay747-svg.github.io/blueprint-portfolio/)

---

## Key Features

- **3D Vanishing Grid Tunnel**: Custom GLSL shader material streaming anti-aliased vector grid lines toward origin `[0, 0, 0]`.
- **Spatial 3D Mindmap Navigation**: Synchronized GSAP camera dolly-ins, wireframe lattice separation, and glowing polyhedral inner core focus.
- **Procedural Web Audio API Sound FX**: 100% code-synthesized audio (servo whooshes, CAD clicks, relay sweeps, and sub-bass boot drone) with zero external MP3/WAV dependencies.
- **Decoupled Topic Exploration**: Dynamic topic modules and point cards that glide smoothly without cluttering 3D camera transitions.
- **Zero Build Tools Required**: Pure HTML5, CSS3, Three.js (r128), and GSAP via high-speed CDN.

---

## Local Development

Run the included lightweight local server:

```bash
python3 serve.py
```

Then visit [http://localhost:8080/](http://localhost:8080/) in your browser.

---

## GitHub Pages Deployment

1. Create a public repository on GitHub named `blueprint-portfolio`.
2. Push this directory:
   ```bash
   git remote add origin https://github.com/ekanshvijay747-svg/blueprint-portfolio.git
   git push -u origin main
   ```
3. In GitHub repo settings, go to **Settings → Pages**, select `Deploy from a branch` (`main` / `/ root`), and save.
