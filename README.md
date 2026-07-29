# VarShal — A Gallery Adrift

An immersive 3D world of floating islands, linked by light to a glowing obelisk at the center of the sky, opening into Meridian, a second city chapter. Built for the **3D Websites Hackathon**.

## ✨ Inspiration
A gallery that drifts instead of standing still — islands scattered across a dusk sky, each holding a fragment of a story about someone who crossed over before you. The project blends a floating-island art gallery (Chapter I: VarShal) with a neon sci-fi city (Chapter II: Meridian), tied together by a light-fragment collection mechanic.

## 🛠️ Tech Stack
- **Three.js** — 3D scene, geometry, lighting, post-processing (bloom)
- **GSAP** — camera flythrough, chapter transitions, UI animation
- Vanilla **HTML/CSS/JS** — no build step, single-page, runs anywhere
- **Web Audio API** — interactive chime SFX
- Custom shaders (GLSL) for the sky dome and aurora ribbons

## 🚀 Run locally
Browsers block ES module imports over `file://`, so serve it instead of double-clicking it:

```bash
cd project
python3 -m http.server 8000
# then open http://localhost:8000
```

