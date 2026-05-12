# C-AIgo

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue)
![IDE](https://img.shields.io/badge/IDE-Visual%20Studio-5c2d91)
![Type](https://img.shields.io/badge/Project-Human%20vs%20AI%20Game-green)

## Overview

This repository is a C++ human-vs-AI board-game project. It is organized as a Visual Studio solution and includes core game logic, AI logic, and local media assets for the interface and gameplay experience.

## Preview

| Board Asset | Demo Video |
| --- | --- |
| ![board](AIgo/AIgo/resource/棋盘3.png) | `AIgo/演示.mp4` |

## Highlights

- human-vs-AI board-game interaction
- C++ class-based design for board state, player logic, and AI logic
- local image, sound, and video assets for the game interface
- preserved Visual Studio solution for direct local build

## Project Structure

- `AIgo/AIgo.sln`: Visual Studio solution
- `AIgo/AIgo/AI.cpp`, `AI.h`: AI-related logic
- `AIgo/AIgo/Chess.cpp`, `Chess.h`: board and rule logic
- `AIgo/AIgo/Man.cpp`, `Man.h`: player-side logic
- `AIgo/AIgo/ChessGame.cpp`, `ChessGame.h`: game orchestration
- `AIgo/AIgo/resource/`: board images, piece assets, and sound effects
- `AIgo/演示.mp4`: local demo video

## Build

Open the solution in Visual Studio:

```text
AIgo/AIgo.sln
```

Then build and run the `AIgo` project from the IDE.

## Notes

- The repository currently includes debug outputs and local build artifacts.
- It is best treated as a preserved course or practice project rather than a fully cleaned release build.
