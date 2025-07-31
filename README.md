# Babylon.js Furniture Visualizer

A simple web-based application built with Babylon.js to create a virtual room where users can place and interact with 3D furniture models.

## Features

* **3D Room Environment**: A basic room with a floor and three walls to serve as the scene.

* **Draggable Furniture**: Load and drag a `.glb` furniture model around the floor of the room.

* **Coordinate Display**: See the real-time position of the furniture on the screen.

* **Dynamic Textures**: Change the material and texture of the furniture with a single click.

## Project Structure

This project follows a simple, organized file structure to make it easy to manage and expand.


## How to Run

1. **Clone the repository**: Clone this project to your local machine.

2. **Open in a browser**: Simply open the `index.html` file in your favorite web browser. There's no need for a local server since all assets are loaded locally or from a CDN.

## How to Use

* **Navigate the scene**: Click and drag with your mouse to rotate the camera. Use the mouse wheel to zoom in and out.

* **Drag the furniture**: Click and hold the main object to drag it along the floor plane.

* **Change the texture**: Click the "Change Texture" button in the top-right corner to change the object's appearance.

## Future Improvements

* Adding more furniture models to choose from.

* Implementing a rotation feature for the furniture.

* Allowing the user to upload their own `.glb` files.

* Creating a user interface to control lighting and room colors.

## Project Structure
```
/my-babylon-project
|-- index.html          # The main HTML file to run the application
|-- assets/             # Folder for all 3D models and textures
|   |-- furniture.glb
|   |-- textures/
|       |-- my_texture.jpg
|-- js/                 # Folder for all JavaScript files
|   |-- main.js         # Contains all the Babylon.js scene logic
|-- css/                # Folder for all CSS styles
|   |-- style.css       # Contains the styling for the UI and canvas
```
