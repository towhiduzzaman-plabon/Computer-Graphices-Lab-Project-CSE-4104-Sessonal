# BAUST Campus & Flying Flag - Computer Graphics Simulation

An interactive 2D/3D graphics simulation of BAUST Campus using Python OpenGL and GLUT.

## 🔴 Live Preview
<img width="800" height="450" alt="demo" src="https://github.com/user-attachments/assets/9358023a-1b3a-418e-a5c5-4acc016f6046" />




## Key Features
- **Official BAUST Architecture**: Complete academic facade with vector crest logo and vertical banner.
- **National Flag Wave Physics**: Realistic multi-segment continuous sine-wave cloth animation.
- **Scan-Line Algorithm**: Midpoint & scan-line filled circle algorithms implemented manually.
- **Day & Night Simulation**: Celestial rotation with dynamic sky color and window light toggling.
- **Interactive 3D Viewing**: Switch between 2D scenery and 3D camera viewpoint with `gluLookAt`.

## 🎮 Keyboard Controls
- `V`: Toggle between 2D Scenery and 3D Perspective Mode
- `P`: Play / Pause all animations
- `D` / `N`: Force Day / Night mode
- `Arrow Keys`: Move 3D camera (X & Z axes)
- `A` / `B`: Adjust camera height (Y-axis)

## 🚀 How to Run Locally
```bash
git clone https://github.com/towhiduzzaman-plabon/Computer-Graphices-Lab-Project-CSE-4104-Sessonal.git https://github.com/towhiduzzaman-plabon/Computer-Graphices-Lab-Project-CSE-4104-Sessonal.git
cd Computer-Graphices-Lab-Project-CSE-4104-Sessonal
pip install -r requirements.txt
python main.py
