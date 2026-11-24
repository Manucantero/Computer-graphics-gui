# Computer Graphics & Interactive GUI Projects

Collection of interactive computer graphics applications developed during my Erasmus exchange, focusing on 2D/3D geometric transformations, camera simulation, and parametric curve interpolation.

## Projects

### 1. Interactive Map Viewer & 3D Camera Simulation (`/map-viewer-3d-camera`)
- **2D Viewport Operations:** Smooth zooming (scaling) centered on the region of interest, panning, and interactive map cropping.
- **3D Camera Simulation:** Real-time simulated camera movement (translation, rotation, and projection) around a 3D cube.

### 2. Parametric Curve Morphing GUI (`/curve-morphing-gui`)
- **Mathematical Curve Evaluation:** Exact evaluation of **Bézier** curves (via Bernstein polynomials) and clamped **B-spline** curves (via Cox–de Boor recursion).
- **Sample-Based Morphing:** Evaluates both curves over a shared normalized parameter domain ($t \in [0, 1]$) and interpolates corresponding sample points, enabling smooth transitions even between curves with different numbers of control points.
- **Interactive Desktop GUI:** Built with Tkinter to add or drag control points directly on a 2D coordinate grid, switch curve types independently, and control the morphing animation via slider or Play/Pause controls.

## Tech Stack

- **Language:** Python 3
- **GUI Framework:** Tkinter (`ttk`)
- **Numerical Computing:** NumPy
- **Environment:** Jupyter Notebook / Python Script

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/Manucantero/computer-graphics-gui.git](https://github.com/Manucantero/computer-graphics-gui.git)
   cd computer-graphics-gui
   ```

2. Install the required dependency:
   ```bash
   pip install numpy
   ```

3. Open the Jupyter Notebook inside `/curve-morphing-gui` (using Jupyter Notebook, JupyterLab, or VS Code) and run all cells to launch the interactive Tkinter window.
