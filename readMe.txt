# 🎓 Virtual Tour of Nile University

An interactive, browser-based 3D virtual tour of the Nile University campus, built with **Three.js** and a custom-modeled campus environment. Navigate the campus as a playable character, explore the buildings, courts, and outdoor spaces, and experience real-time shadows and reflections powered by ray casting.

🏆 **Winner — Best Project in 3D Computer Graphics & Visualization**, Undergraduate Research Forum (UGRF)

---

## 📖 Overview

This project reconstructs the Nile University campus as a fully explorable 3D environment. The campus geometry was derived from official **AutoCAD** architectural drawings provided by the university's Engineering Department, then modeled and textured in **SketchUp Pro** before being exported to the web-friendly **GLTF/GLB** format for real-time rendering with Three.js.

A controllable character walks freely across the reconstructed terrain, with movement, running, ground alignment, and dynamic shadows all handled procedurally through ray tracing — no baked animations for positioning are required.

### What's included in the campus model
- 🏢 Two main academic buildings
- 🎭 Roman Theatre
- 🚪 Main gate and campus entrance
- 🏛️ Campus pergola
- ⚽ Football court
- 🏀 Basketball court
- 🎾 Padel courts
- 🌳 Surrounding campus terrain and outdoor grounds

---

## ✨ Features

- **Free-roam 3D exploration** of the full campus using a controllable character
- **WASD movement** with **Shift-to-run** toggle
- **Real-time ground detection** via raycasting, so the character follows the terrain's elevation naturally (ramps, slopes, stairs, etc.)
- **Dynamic contact shadow** that projects beneath the character and follows the ground surface
- **Reflective ground plane** for added visual realism
- **Custom gradient sky background**
- **Orbit camera controls** with damping for smooth, cinematic movement
- **Fully responsive** rendering that adapts to window resizing
- Character animations (Idle / Walk / Run) blended smoothly via animation mixing

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| [Three.js](https://threejs.org/) | Core 3D rendering engine |
| GLTFLoader | Loading the campus and character 3D models |
| OrbitControls | Camera navigation |
| Reflector.js | Real-time reflective ground surface |
| SketchUp Pro | 3D modeling of the campus from AutoCAD drawings |
| AutoCAD | Source architectural drawings (provided by Nile University's Engineering Department) |

---

## 📁 Project Structure

```
Virtual-Tour-of-Nile-University/
├── Project.html          # Main entry point — scene setup, controls, and render loop
├── Soldier.glb           # Animated character model (Idle/Walk/Run)
└── README.md
```

### `Project.html`
The main file that initializes and runs the entire experience:
- Sets up the Three.js scene, camera, and renderer
- Configures ambient, directional, point, and hemisphere lighting
- Loads the campus model and the animated character model
- Implements the `CharacterControls` class, handling movement, rotation, animation blending, and ground-following via raycasting
- Adds a reflective ground plane and gradient sky background
- Handles window resize events for a responsive viewport


---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.)
- A code editor (VS Code recommended) if you want to explore or modify the code
- A local development server (browsers block local file loading of 3D assets due to CORS restrictions)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/RaniaMostafa0/Virtual-Tour-of-Nile-University.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Virtual-Tour-of-Nile-University
   ```

3. **Serve the project locally**

   Since the project loads `.glb` model files, it needs to be run through a local server rather than opened directly as a file.

   **Option A — VS Code Live Server**
   - Open the project folder in VS Code
   - Right-click `Project.html` → **Open with Live Server**

   **Option B — Python's built-in server**
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000/Project.html` in your browser.

---

## 🎮 Controls

| Input | Action |
|---|---|
| `W` `A` `S` `D` | Move character |
| `Shift` | Toggle run |
| Mouse drag | Orbit camera |
| Scroll wheel | Zoom in/out |

---

Project created and developed as part of a Computer Graphics course project.

---

## 📄 License

This project is provided for educational and portfolio purposes. If you'd like to reuse or build on it, please reach out or open an issue first.
