Virtual Tour of Nile University
Project Description:
The Nile University Virtual Tour project aims to create an immersive, interactive 3D tour of Nile University’s campus using Three.js. This project will provide a digital representation of the university, allowing users to explore the campus virtually. The 3D model will be created using SketchUp Pro, then exported to the GLTF format for compatibility with Three.js. Key features include dynamic lighting, realistic camera controls, and the ability to interact with the environment in a user-friendly and engaging way. The goal is to offer prospective students, parents, and visitors a realistic and accessible experience of the campus without the need for physical travel.

Purpose:
The purpose of the Nile University Virtual Tour project is to bridge the gap for prospective students, parents, faculty, and international visitors who are unable to visit the campus physically. By offering a detailed and realistic 3D tour of the campus, this project aims to enhance the decision-making process for prospective students and provide a comprehensive virtual experience. It also seeks to showcase Nile University’s facilities and campus environment in a visually captivating and interactive format, making it accessible to a global audience.

Objective:
The objective of this project is to develop a fully interactive 3D virtual tour of Nile University that accurately represents the campus environment. This will involve:
- Creating the 3D model of the university using SketchUp Pro.
- Exporting the model to GLTF format to ensure compatibility with Three.js.
- Loading and rendering the model in Three.js, integrating realistic lighting and shading.
- Implementing dynamic camera controls to allow users to explore the campus from different perspectives.
- Enhancing interactivity with smooth navigation, realistic light effects, and detailed rendering to provide users with an immersive experience of the university campus.

File Descriptions
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