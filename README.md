# 🏅 Olympic Logo using OpenGL

This project is a simple OpenGL-based rendering of the Olympic rings symbol using animated 3D toruses. It demonstrates basic 3D graphics concepts such as lighting, transformations, and animation.

![Olympic Rings Demo](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Olympic_rings_without_rims.svg/320px-Olympic_rings_without_rims.svg.png)

## 🚀 Features

- Renders 3D torus shapes to form the Olympic logo
- Smooth color transitions and rotations for animation
- Uses lighting and shading for realistic rendering
- Keyboard-controlled reinitialization

## 📋 Requirements

To run this project, make sure you have:

- A C++ compiler
- OpenGL and GLUT installed (e.g., FreeGLUT on Windows or `freeglut3-dev` on Linux)
- A basic build system (like Make, CMake, or g++ CLI)

## 🛠️ How to Build & Run

### Linux / macOS

```bash


Windows (MinGW)
g++ -o olympic_logo main.cpp -lGL -lGLU -lglut
./olympic_logo

```

Make sure the required DLLs (freeglut.dll, etc.) are available in your PATH.

⌨️ Controls
Spacebar: Reinitialize the animation with random positions and rotations

ESC: Exit the program

