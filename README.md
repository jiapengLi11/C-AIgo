# C-AIgo

## Overview

This repository is a C++ human-vs-AI board-game project. It is organized as a Visual Studio solution and includes core game logic, AI logic, and local media assets for the interface and gameplay experience.

## Tech Stack

- C++
- Visual Studio solution / project files
- Local image and audio assets

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
- This project is best treated as a preserved course or practice project rather than a cleaned release build.
- A good next cleanup step would be removing `Debug/`, `x64/Debug/`, and user-specific project files.
