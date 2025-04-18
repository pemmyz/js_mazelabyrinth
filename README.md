# js_mazelabyrinth


### Play it now: https://pemmyz.github.io/js_mazelabyrinth/js_mazelabyrinth.html


# Maze Game WebGL

A 3D maze exploration game rendered using WebGL with:
- Intelligent bot navigation (BFS, DFS, A*, and Explore)
- Fullscreen and draggable 2D map overlay
- Auto-starting bot if the player is idle
- Dynamic fog-of-war style map discovery
- Exit detection and automatic maze regeneration
- Smooth player movement and rotation animations

![screenshot](preview.png) <!-- Optional screenshot if available -->

---

## 🎮 Features

- 🔁 **Procedural Maze Generation**
  - NetHack-style rooms and corridors
  - Auto-connected with hallways
  - Randomized on each run (with seeding)
  
- 🤖 **Bot Modes**
  - `1`: Breadth-First Search (BFS)
  - `2`: Depth-First Search (DFS)
  - `3`: A* Search
  - `4`: Explore all rooms then find the exit
  - Bot automatically starts after 7s of idle

- 🧭 **2D Map Overlay**
  - Toggle full map view with **M**
  - Drag to pan map view
  - Minimap displayed by default

- 🕹️ **Smooth Player Controls**
  - `W / ↑`: Move Forward
  - `S / ↓`: Move Backward
  - `A / ←`: Turn Left
  - `D / →`: Turn Right

- ❓ **Help Overlay**
  - Toggle with **H** to show controls and keys

---

## 🧪 Try It Out

1. Clone or download this repo
2. Run a local server (since WebGL/Canvas may require it):

```bash
# Python 3.x
python -m http.server
