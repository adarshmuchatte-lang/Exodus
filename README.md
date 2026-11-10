[project_readme.md](https://github.com/user-attachments/files/34653253/project_readme.md)
<div align="center">

# ✦ EXODUS — HUMANITY'S LAST SHIP
### *The Interstellar Migration Program & Interactive 3D Web Experience*

[![Live Demo](https://img.shields.io/badge/status-live%20production-blue?style=for-the-badge&logo=vercel)](https://github.com/adarshmuchatte-lang)
[![WebGL](https://img.shields.io/badge/WebGL-Custom%20Shaders-emerald?style=for-the-badge&logo=webgl)](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)
[![Vanilla JS](https://img.shields.io/badge/Zero-Heavy%20Dependencies-orange?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

<p align="center">
  <b>Earth was only the beginning. Our future lies among the stars.</b>
</p>

</div>

---

## 🌌 Overview

**EXODUS** is an immersive, cinematic, scroll-driven web experience and interactive 3D generation vessel visualization. Built with high-performance Vanilla JavaScript and custom WebGL shaders, it pushes browser graphics to deliver an atmospheric journey through deep space, complete with real-time telemetry, rotating artificial-gravity habitats, and celestial orbital mechanics.

Designed from the ground up for elite creative developer portfolios and interactive storytelling, EXODUS combines editorial typography with uncompromising technical engineering.

---

## ✨ Key Features

* **Custom WebGL Engine (Zero External Frameworks):** Hand-written shaders (`WebGLRenderingContext`) rendering the EXODUS-01 generation ship, rotating habitats, planetary bodies, and celestial rings at 60 FPS without Three.js or heavy dependencies.
* **Interactive Orbital Mechanics:** Physics-based yaw rotation, mouse-driven camera parallax, touch-device support, and keyboard controls (`Arrow Keys` / `Warp` trigger).
* **Atmospheric Starfield Generator:** Procedurally generated dual-layer background starfield with dynamic opacity and depth scaling.
* **Cinematic Editorial Design:** Deep space-black aesthetics (`#06090e`), crisp monochrome typography (`Arial` & monospace telemetry), subtle glassmorphism (`backdrop-filter: blur`), and responsive grid layouts.
* **Live Telemetry HUD:** Real-time mission stats tracking journey completion percentage, crew count ticker (12,480 souls), and structural system readouts.
* **Interactive Vessel Systems Explorer:** Modular breakdown of the Habitation Ring, Biosphere, Propulsion cores, and Medical archives.
* **Accessibility & Graceful Degradation:** Full support for `prefers-reduced-motion`, keyboard focus states, responsive mobile breakpoints, and automatic WebGL-to-canvas fallback handling.

---

## 🛠️ Tech Stack

* **Core:** HTML5, CSS3, ES6+ JavaScript (Vanilla)
* **Graphics:** WebGL API, GLSL Fragment & Vertex Shaders, HTML5 2D Canvas Context
* **Typography & UI:** Custom Monospace HUD, CSS Grid & Flexbox, CSS Custom Properties (`:root`)
* **Performance:** Optimized requestAnimationFrame render loops, pixel-ratio clamping, and Intersection Observers

---

## 🚀 Quick Start & Local Execution

To run **EXODUS** locally on your machine, follow these simple steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/adarshmuchatte-lang/exodus.git
   cd exodus
   ```

2. **Open the project:**
   Simply double-click `EXODUS-Humanity-s-Last-Ship.html` or open it with your favorite browser (Chrome, Safari, Firefox, Edge).

3. **Development Server (Recommended):**
   If you use VS Code, open the folder and launch with **Live Server**, or run a local python server:
   ```bash
   python3 -m http.server 8000
   ```
   Then navigate to `http://localhost:8000/EXODUS-Humanity-s-Last-Ship.html` in your browser.

---

## 🕹️ Interactive Controls

| Action | Input / Control |
| :--- | :--- |
| **Rotate Vessel** | Click & Drag across the hero canvas |
| **Keyboard Orbit** | Use `←` and `→` Arrow Keys |
| **Reset View** | Click the `DRAG TO ORBIT · RESET ↺` button |
| **Explore Systems** | Click any button in *The Vessel* section |
| **Smooth Anchor Jump** | Click navigation links in the top header |

---

## 📈 Mission Telemetry & Architecture

```
EXODUS-01 VESSEL SPECIFICATIONS
├── [01] HABITATION RING  → 1.2 km artificial gravity deck
├── [02] BIOSPHERE        → 96% closed-loop water recycling & food growth
├── [03] PROPULSION       → Dual-core fusion drives with shielded engineering
└── [04] MEDICAL ARCHIVE  → 24/7 neonatal care & genetic heritage vault
```

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

<div align="center">
  <small><b>2189 — 2389 &nbsp; / &nbsp; THE HUMAN STORY CONTINUES</b></small><br>
  <sub>Crafted with passion for immersive web experiences.</sub>
</div>
