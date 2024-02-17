# CubeFlyer Project Documentation

## Guide to Running the Project Locally

To run the CubeFlyer project locally, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone <repository_url>
   ```

2. Navigate to the `game` directory:
   ```bash
   cd CubeFlyer/game
   ```

3. Open the `index.html` file in a web browser. You can do this by either double-clicking on the file or right-clicking and selecting "Open with" and choosing your preferred browser.

4. The game should now load in your browser, allowing you to fly the cube through the obstacles.

## Code Structure Documentation

The CubeFlyer project has the following structure:

```
CubeFlyer
│
└── game
    ├── index.html
    ├── assets
    │   ├── models
    │   │   ├── cube.glb
    │   │   └── obstacles
    │   │       ├── obstacle1.glb
    │   │       └── obstacle2.glb
    │   └── textures
    │       └── skybox
    │           ├── back.png
    │           ├── bottom.png
    │           ├── front.png
    │           ├── left.png
    │           ├── right.png
    │           └── top.png
    ├── css
    │   └── style.css
    └── js
        ├── babylon.js
        ├── babylon.max.js
        ├── babylonjs.loaders.js
        └── game.js
```

- `index.html`: The main HTML file that loads the game.
- `assets`: Directory containing all assets used in the game, such as models and textures.
- `css`: Directory containing the CSS styles for the game interface.
- `js`: Directory containing JavaScript files for the game logic and Babylon.js library.

## Features Documentation

### Obstacle Courses

The CubeFlyer game features obstacle courses that the player navigates the cube through. These courses are designed to challenge the player's flying skills and spatial awareness.

#### Obstacle Models

The obstacle models are stored in the `assets/models` directory. Each obstacle is represented by a `.glb` file format.

#### Skybox Textures

The skybox textures, which provide the background environment for the game, are located in the `assets/textures/skybox` directory. These textures create an immersive atmosphere for the player.

### Flying Mechanics

The CubeFlyer game utilizes Babylon.js to create realistic flying mechanics for the cube. Players can control the cube's movement using keyboard inputs.

### Score Tracking

The game keeps track of the player's score based on their performance in navigating the obstacle courses. Players can aim to beat their high score or compete with friends for the highest score.

This documentation provides an overview of the main features of the CubeFlyer project. For more detailed information or specific implementation details, please refer to the codebase and relevant documentation within the project repository.
