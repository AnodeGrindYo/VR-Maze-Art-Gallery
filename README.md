# Virtual Reality Art Exhibition in a procedurally generated maze

Welcome to my art exhibition, a browser-based VR experience where a maze is procedurally generated, and every wall of the maze is adorned with some of my drawings. 

![Virtual Maze Screenshot](your-screenshot-link-here.png)

## Demo

Experience the maze live [here](https://cdn.discordapp.com/attachments/932672918859702355/1152162788165296138/image.png).

## Features

- **Procedural Maze Generation**: The maze is randomly generated each time to ensure a fresh experience.
- **Unique Wall Textures**: Every maze wall showcases one of the drawings, transforming the maze into an art exhibition.
- **VR Ready**: Engage in a VR-based navigation experience.
- **Solution Rendering**: For those who need a little help, a solution path is available.

## Configuration Constants

```javascript
const SIZE = 50;        // Defines the size of the maze.
const MOVE_STEP = 1;    // Movement step size.
const TILE_SIZE = 4;    // Size of each tile in the maze.
```

## How It Works

1. The maze is randomly generated using a depth-first search algorithm.
2. Walls of the maze are assigned a random image from a collection of drawings.
3. Users can navigate using arrow keys.
4. A solution, marked with arrows, can guide the user from the start to the finish of the maze.



---

Designed with :heart: by [AnodeGrindYo](https://codepen.io/Adr_G).
