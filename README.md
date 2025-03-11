# GLB Viewer

A simple web-based 3D model viewer for GLB files using Three.js.

## Features

- Open GLB files via file dialog or drag-and-drop
- Camera controls (orbit, pan, zoom)
- Model auto-centering and scaling
- Toggle wireframe mode
- Toggle auto-rotation
- Reset view function
- Loading indicator
- Responsive design

## Setup

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/glb-viewer.git
   cd glb-viewer
   ```

2. Serve the files with a local web server:

   Using Python:
   ```
   # Python 3
   python -m http.server
   
   # Python 2
   python -m SimpleHTTPServer
   ```
   
   Using Node.js (after installing `http-server`):
   ```
   npx http-server
   ```

3. Open your browser and navigate to `http://localhost:8000` (or whatever port your server is using).

## Usage

1. Click the "Open GLB File" button to select a GLB file from your device, or drag and drop a GLB file onto the page.
2. Use mouse/touch controls to manipulate the 3D view:
   - Left click/touch + drag: Rotate the camera around the model
   - Right click/touch + drag: Pan the camera
   - Scroll/pinch: Zoom in/out

## Controls

- **Open GLB File**: Opens a file dialog to select a GLB file
- **Reset View**: Resets the camera to the default position
- **Toggle Wireframe**: Switches between solid and wireframe rendering
- **Toggle Rotation**: Turns auto-rotation on/off

## Dependencies

This project uses:
- [Three.js](https://threejs.org/) for 3D rendering
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) for camera manipulation
- [GLTFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader) for loading GLB files

## Browser Support

This viewer works on all modern browsers that support WebGL, including:
- Chrome
- Firefox
- Safari
- Edge

## License

[MIT License](LICENSE)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements

- Three.js team for their excellent 3D library
- The Khronos Group for the glTF/GLB format
