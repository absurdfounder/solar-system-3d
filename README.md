# 🌌 3D Solar System

An interactive 3D Solar System visualization built with [Three.js](https://threejs.org/) — no build step required.

![Three.js](https://img.shields.io/badge/Three.js-r165-black?logo=three.js)
![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-ES2022-yellow?logo=javascript)
![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Features

- ☀️ **Sun** with point light and glow effect
- 🪐 **All 8 planets** — Mercury through Neptune — with accurate relative sizes and orbital speeds
- 💫 **Orbit rings** visible for every planet
- 🪐 **Saturn's ring system** rendered with custom geometry and UV mapping
- 🔄 **Axial rotation** on each planet plus orbital revolution around the Sun
- 🖱️ **Mouse drag** to orbit the camera (Three.js OrbitControls)
- 🎨 **Physically-based lighting** — ambient + point light from the Sun
- ⚡ **Zero build step** — open `index.html` directly in any modern browser

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/absurdfounder/solar-system-3d.git
cd solar-system-3d

# Open in browser — no server needed
open index.html
```

Or just [download the ZIP](https://github.com/absurdfounder/solar-system-3d/archive/refs/heads/main.zip) and open `index.html`.

## 🎮 Controls

| Action | Control |
|--------|---------|
| Orbit camera | Left-click + drag |
| Zoom | Scroll wheel |
| Pan | Right-click + drag |

## 🔧 Tech Stack

- **Three.js r165** — loaded via native ES module importmap (no bundler)
- **Vanilla JavaScript** — ES2022, zero dependencies
- **Single HTML file** — everything in `index.html`

## 🪐 Planets

| Planet | Relative Size | Orbital Period (scaled) |
|--------|--------------|------------------------|
| Mercury | 0.38× Earth | 0.24 yr |
| Venus | 0.95× Earth | 0.62 yr |
| Earth | 1.0× | 1.0 yr |
| Mars | 0.53× Earth | 1.88 yr |
| Jupiter | 11.2× Earth | 11.86 yr |
| Saturn | 9.4× Earth | 29.46 yr |
| Uranus | 4.0× Earth | 84.0 yr |
| Neptune | 3.9× Earth | 164.8 yr |

## 📄 License

MIT — free to use, remix, and share.
