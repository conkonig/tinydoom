# TinyDoom

**A Doom-style 2.5D raycasting game built in pure JavaScript + HTML5 Canvas**  
Playable demo in **333 lines of code** (or less, depending on formatting).

TinyDoom is a compact, from-scratch recreation of the classic 2.5D raycasting technique pioneered by John Carmack for the original *Doom* (1993). It runs entirely in the browser with no external libraries or frameworks—just vanilla JavaScript, Canvas 2D, and clever math.

This tiny engine delivers pseudo-3D rendering, textured walls, player movement, rotation, collision detection, and a simple map—all squeezed into minimal code while staying true to the spirit of early 90s FPS tech.

### Why This Project Exists

The spark came from a few fun intersections:

1. While building an agentic container orchestration tool styled like Windows 95 (complete with desktop icons for services), I missed the iconic Doom guy on the desktop. Since it was a web app, I wanted a tiny, embeddable Doom easter egg.

2. The recent buzz around "Can it run Doom?"—especially the wild demo of lab-grown human brain cells playing Doom—reminded me how elegant and efficient Carmack's raycasting really was. I wanted to see how cleanly it could be implemented today in modern JavaScript.

3. Cloudflare's WASM Doom port is impressive. TinyDoom started as curiosity about whether a similar lightweight raycaster could become a foundation for WebSocket-based multiplayer experiments.

4. Sometimes you just need a satisfying side project when the day is done.

The result: a surprisingly playable micro-Doom tribute in **exactly 333 lines** (unminified, nicely formatted). It's obviously a shadow of the full game—no enemies, weapons, or levels yet—but it captures the core magic of raycast rendering with very little code.

The goal? Prove that with imagination and tight code, you can still build impressive things in <1000 lines. Maybe even push toward something closer to the real Doom experience.

### Features

- Classic 2.5D raycasting engine
- Perspective-correct wall texturing
- Player movement (WASD + mouse look / arrow keys)
- Basic collision detection against map walls
- Simple grid-based map
- Smooth 60 FPS rendering in `<canvas>`
- Zero dependencies

### Play the Demo

→ **[Live Demo](https://conkonig.github.io/tinydoom/)** (replace with your actual link)

### Tutorial / Walkthrough

I wrote a step-by-step tutorial explaining how the raycasting works, how the code is structured, and key optimization tricks:

→ **[Read the Tutorial](tutorial.md)**

### Contributing

Contributions are very welcome!  
Ideas for evolution:

- Add floor/ceiling textures
- Sprites / enemies
- Weapons & shooting
- Sound effects / music
- Multiple levels
- WebSocket multiplayer proof-of-concept
- Performance optimizations
- Minification challenges

Feel free to open issues, PRs, or fork it and take it in wild directions. Let's see how far we can push "Doom in the browser" with minimal code.

Happy raycasting!