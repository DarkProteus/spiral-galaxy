# Spiral Galaxy

**Live demo:** https://darkproteus.github.io/spiral-galaxy/

An animated spiral galaxy made with Three.js, in a single HTML file.

The arms are a density wave. Each star moves along its own elliptical orbit, and each orbit is turned a little more than the one inside it. The arms form where orbits crowd together, so the pattern holds steady instead of winding up over time. About 145k particles are animated on the GPU in a vertex shader, with bloom added on top.

## Run

```
python3 -m http.server
```

Then open http://localhost:8000. Opening the file directly may not work, because browsers often block module imports from `file://` pages.

## Controls

Drag to orbit and scroll to zoom. The panel adjusts arm twist, orbit eccentricity, time scale, pattern speed, star and gas counts, star size and bloom.
