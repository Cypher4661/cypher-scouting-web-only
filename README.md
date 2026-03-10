# Cypher Scouting (Web-only)

[Live Demo](https://cypherscouting.netlify.app/)

> This repository contains the static web build of the Cypher Scouting app (Flutter web output only).

## 🚀 What is this?
Cypher Scouting is a scouting system for robotics competitions, made to capture match data, team performance, and strategy insights. This repo contains the built web assets (HTML/CSS/JS/png) ready to host via Netlify, GitHub Pages, or any static file server.

## ⚙️ Included files
- `index.html`
- `main.dart.js`
- `flutter.js`, `flutter_bootstrap.js`, `flutter_service_worker.js`
- `manifest.json`, `version.json`
- `assets/` (images, fonts, packages, shaders)
- `canvaskit/` (optional Flutter CanvasKit renderer files)
- `icons/`

## 🌎 Supported platforms
- Desktop browsers (Chrome, Edge, Firefox, Safari)
- *Mobile browsers may not be fully supported* (already noted in the original repo text)

## 🧩 How to run locally (static files)
1. Clone this repo:
   ```bash
   git clone https://github.com/Cypher4661/cypher-scouting-web-only.git
   cd cypher-scouting-web-only
   ```
2. Start a local HTTP server (recommended):
   ```bash
   npx serve .
   ```
3. Open `http://localhost:3000` in your browser.

## 📦 How to deploy
- Netlify: drag and drop the folder or connect repo and set publish directory to `/`
- GitHub Pages: set branch to `main` and folder to `/` (or use the `docs/` strategy)
- Vercel: set framework to "Other", output directory to `/`

## 🛠️ Notes for contributors
- This repo is a compiled output of a Flutter project, not the source.
- If you want to change behavior, edit the original Flutter project and rebuild with `flutter build web`.
- Keep asset hashes and `version.json` updated when redeploying.

## 📣 Quick callouts
- Single-page app with Flutter web runtime
- Designed for scouting and data capture in competitive environments
- Works best on desktop and modern browsers

---

Made with :heart: for Cypher teams.

