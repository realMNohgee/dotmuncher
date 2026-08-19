# DotMuncher 🟡

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Deployed on Vercel](https://img.shields.io/badge/deployed%20on-Vercel-black?logo=vercel)

**A Pac-Man-style maze chase** — eat every dot, grab the power pellets to turn the tables on four ghosts, and clear the maze.

A single-file HTML5 canvas game in vanilla JavaScript with a 21×23 grid maze, four ghosts with distinct AI behaviors, and retro terminal-styled chrome.

## How to play

| Key | Action |
|---|---|
| ↑ ↓ ← → / W A S D | Move / change direction |
| Space | Play again after game over |

- **Goal:** eat every dot to clear the level and advance.
- **Power pellets** make the ghosts frightened (slower + edible) — eat them for 200/400/800/1600 points.
- **Ghosts** each chase differently (chase, ambush, patrol, wander); touching one costs a life unless it's frightened.
- **Tunnels** on the left and right edges wrap around to the other side.
- You start with **3 lives**; each cleared level speeds the ghosts up.

## Tech stack

- Single-file **HTML5 `<canvas>`** + **vanilla JavaScript**, monospace terminal styling.
- No build step, no dependencies — just open `index.html`.

## Run locally

```bash
git clone git@github.com:realMNohgee/dotmuncher.git
cd dotmuncher
open index.html
```

## License

MIT — see [LICENSE](LICENSE).
