# Frontline Defense 3D

A 3D tower defense game that runs entirely in the browser — no build step, no
install, no server. Open the page and play.

**▶ [Play it here](https://fanaustinca.github.io/frontline-defense-3d/)**

![built with three.js](https://img.shields.io/badge/three.js-r128-black)

## The game

Your base sits on the shore of a lake, fed by a river that winds down out of the
mountains. Enemies march in from tunnel mouths bored into the valley walls and
sail gunboats down the river. Hold the line.

- **One road in at first.** A second road joins the main line at a junction
  further out at wave 11, and a third joins further out still at wave 17 — so
  everything funnels down a shared final approach you can fortify once.
- **Your territory grows outward** from the base every few waves, opening new
  ground to build on.
- **Nine buildings**, each with two named upgrade branches that visibly change
  the model: machine gun nests, artillery, EMP towers, sniper towers, army camps
  and factories that send troops and armed trucks out to fight, a shipyard for
  the river, an airfield whose plane strafes and bombs, and walls that enemies
  have to break through.

## Controls

| | |
|---|---|
| Drag | Orbit the camera |
| Scroll | Zoom |
| Right-drag / WASD | Pan |
| 1–9 | Pick a building |
| Click | Place it, or select one to upgrade |
| Shift + click | Place several |
| Space | Start the next wave |

## Running it locally

Just open `index.html` in a browser. Everything is vendored, so it works from
`file://` with no server.

## Files

- `index.html` — the whole game: terrain generation, rendering, and gameplay
- `lib/three.min.js` — three.js r128, vendored so the page works offline
- `classic-2d.html` — the original 2D canvas version, kept for posterity

## Credits

Built with [three.js](https://threejs.org) (MIT). The terrain, water, roads,
tunnels and every model are generated procedurally in code — there are no
external assets.
