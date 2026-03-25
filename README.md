# 🌍 3D Solar System

An interactive 3D solar system visualization built with [Three.js](https://threejs.org/). All 8 planets orbit the Sun with accurate relative sizes and speeds. Runs entirely in the browser — no build step, no server required.

![Solar System Preview](https://i.imgur.com/placeholder.png)

## ✨ Features

- ☀️ **Sun** with emissive glow and point lighting
- 🪐 **All 8 planets** — Mercury through Neptune
- 🪐 **Saturn's rings** — tilted at 26.7° (real axial tilt)
- 🌌 **8,000-star background** field
- 🔵 **Orbit path rings** for each planet
- 🏷️ **Planet name labels** projected in screen space
- 🖱️ **Mouse drag** to rotate camera (OrbitControls)
- 🔍 **Scroll to zoom**, right-drag to pan
- ⚡ **Speed slider** — adjust orbit animation speed in real time
- 📐 **Responsive** — works on any screen size

## 🚀 Quick Start

Just open `index.html` in any modern browser:

```bash
# Option 1: Open directly
open index.html   # macOS
start index.html  # Windows

# Option 2: Serve locally (optional)
npx serve .
# then visit http://localhost:3000
```

> **No build step needed.** Three.js loads from CDN via ES module importmap.

## 🎮 Controls

| Action | Control |
|--------|---------|
| Rotate view | Left mouse drag |
| Zoom in/out | Scroll wheel |
| Pan | Right mouse drag |
| Speed up/slow orbits | Speed slider (bottom-left) |

## 🪐 Planet Data

Sizes and orbital periods sourced from [NASA Planetary Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/).

> Orbit distances are logarithmically compressed for visual clarity — true astronomical distances would make inner planets invisible at this scale.

| Planet | Real Diameter | Orbital Period |
|--------|--------------|----------------|
| Mercury | 4,879 km | 88 days |
| Venus | 12,104 km | 225 days |
| Earth | 12,756 km | 365 days |
| Mars | 6,792 km | 687 days |
| Jupiter | 142,984 km | 11.9 years |
| Saturn | 120,536 km | 29.5 years |
| Uranus | 51,118 km | 84 years |
| Neptune | 49,528 km | 164.8 years |

## 🛠️ Tech Stack

- [Three.js r165](https://threejs.org/) — 3D WebGL renderer
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) — mouse interaction
- Vanilla HTML + JavaScript, ES modules
- Zero dependencies beyond Three.js CDN

## 📁 Files

```
solar-system-3d/
└── index.html    ← everything in one file, open in browser
└── README.md     ← this file
```

## 📄 License

MIT — free to use, modify, and share.

---

Built with ❤️ using Three.js
