# 2D Game Engine

A simple 2D game engine built with **C++**, **SDL2**, and **Lua**.  
This project is currently **in progress** and serves as a learning tool to explore C++ and game development.

## Features (Planned)
- 🕹️ Game object management.
- 🎮 Simple input handling.
- 🎨 Basic rendering with SDL2.
- 🛠️ Scripting with Lua for game logic.
- ⚡ Easy setup and extensibility.

## Why This Project?
The main goal is to build a lightweight game engine to:
- Deepen understanding of **C++ programming**.
- Learn how to integrate **SDL2** for rendering and input handling.
- Explore **Lua scripting** for game logic.
- Create a foundation for experimenting with game mechanics.

## Requirements
To run this project, you'll need:
- A C++17-compatible compiler.
- SDL2 development libraries.
- Lua 5.4 or later.

## Build Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/2d-game-engine.git
   cd 2d-game-engine
2. Compile:
   g++ -Wall -std=c++17 -I"./libs/" src/*.cpp -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_mixer -llua5.4  -o gameengine;
