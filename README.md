# A-Frame Solar System Simulation

This is a beginner-friendly 3D solar system model built using [A-Frame](https://aframe.io/), a web framework for building virtual reality experiences. Each planet rotates on its axis and revolves around the sun in an orbital path, creating an animated solar system in the browser.

### 🌟 Features
- Realistic orbital animation for each planet
- Planet textures mapped using A-Frame assets
- Scaled-down distances and radii for better visualization
- Custom skybox with stars
- Adjustable camera controls

### 🔧 Tech Stack
- HTML
- A-Frame
- WebGL (via Three.js)

### 🧠 What I Learned
- Basics of VR and 3D development with A-Frame
- Mapping textures and animating rotations
- Structuring hierarchical entities in A-Frame for orbital motion
- Debugging browser-based 3D environments

### 🚀 How to Run
1. Clone the repo or download the `.html` file.
2. Ensure you have a local HTTP server (e.g. Python’s `http.server`) to load textures.
3. Place your `planet_textures` folder alongside the HTML file.
4. Open the HTML in a browser through your local server.

```bash
# Example using Python
python3 -m http.server 5500
# Then open http://localhost:5500 in your browser
