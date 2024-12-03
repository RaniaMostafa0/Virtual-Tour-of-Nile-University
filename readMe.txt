Virtual Tour of Nile University
File Descriptions:
1. Project.html
Purpose: This is the main HTML file that serves as the entry point for the virtual tour. It contains the structure of the web page and the necessary scripts to initialize and run the Three.js environment.
Content:
- Imports Three.js, GLTFLoader, and OrbitControls to render the 3D scene and handle user interaction.
- Initializes the scene, camera, and renderer for displaying the 3D model.
- Loads the GLTF model of Nile University.
- Configures lighting and camera controls to create a smooth and interactive user experience.
- Handles window resizing for responsive design.
2. NU 3D MODEL 3.glb
Purpose: This is the GLTF 3D model of Nile University. It is the primary 3D asset used in the virtual tour.
Content: The GLTF file contains all the 3D geometry, textures, and materials of the campus buildings, terrain, and other elements modeled in SketchUp Pro and exported to GLTF format.

Project Setup Instructions
To run the Nile University Virtual Tour project locally, follow the steps below:
Prerequisites:
Make sure you have the following installed:
- A modern web browser (Google Chrome, Firefox, etc.) to view the virtual tour.
- A code editor (such as VSCode) to view and modify the files if needed.
1. Clone the Repository
Clone the repository to your local machine using the following command:
git clone https://github.com/RaniaMostafa0/Virtual-Tour-of-Nile-University.git
2. Navigate to the Project Directory
Open the terminal or command prompt and navigate to the project folder:
cd path/to/Virtual-Tour-of-Nile-University
3. Setup and Run the Project
There are no special dependencies to install for this project since it relies entirely on browser-based JavaScript and Three.js. However, you can follow the below steps to get started:
1. Host the project on a local server, you can use a simple HTTP server like VSCode Live Server:
Using VSCode Live Server:
- Open the project folder in VSCode.
- Right-click on the Project.html file and select "Open with Live Server".
4. Exploring the Virtual Tour
- Use the mouse or touchpad to drag and rotate the camera.
- Scroll or use the arrow keys to zoom in and out.

Technologies Used
1. Three.js – A JavaScript library used for rendering 3D models and creating interactive scenes.
2. GLTF – A 3D model format used for efficient, browser-compatible rendering of 3D assets.
3. SketchUp Pro – A 3D modeling software used to create the model of Nile University.
