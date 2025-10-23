# Beagle Bros Visualizations (Standard + Advanced)

A single-file HTML playground for math/physics visualizations.  
- **Standard mode:** 2×2 grid, 64-piece library (Lissajous, roses, spirographs, harmonographs, spirals).  
- **Advanced mode:** full-screen single canvas with heavy hitters: **SDF ray marcher**, **Mandelbulb ray-march**, **O(N²) N‑body** with trails, and **Joukowski airfoil streamlines**.

## Quick start
Just open `index.html` in your browser. No build, no deps.

## Features
- Origin centered in every canvas (optional Y↑).
- Shuffle, per-pane lock (standard), contextual hover popups.
- Advanced mode swaps to a single large canvas and shuffles only within the advanced library.

## Publish on GitHub Pages
1. Create a new repo on GitHub (suggested name: `beagle-bros-visualizations`).  
2. Commit `index.html` (and this README, LICENSE).  
3. In **Settings → Pages**, set **Source: Deploy from a branch**, **Branch: `main`**, **/ (root)**.  
4. Visit the Pages URL GitHub shows.

## CLI one-liner (uses GitHub CLI)
```bash
# from the folder with index.html
git init
git add .
git commit -m "Initial commit: Standard + Advanced visualizations"
gh repo create Capitali/beagle-bros-visualizations --public --source=. --remote=origin --push
# enable Pages from the UI (Settings → Pages → Deploy from branch → main /root)
```

## License
MIT
# BBrosStylin
