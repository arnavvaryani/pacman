# Pacman Project 

## Overview
This project is a recreation of the classic arcade game Pacman, developed using Turbo C with graphics.h library. It features Pacman navigating through a maze, eating pellets, avoiding ghosts, and scoring points. The game is built for systems running DOS with graphics support.

## System Requirements
- Operating System: Windows, Mac or Linux
- Compiler: Turbo C/C++
- Graphics: BGI (Borland Graphics Interface) support

## Installation
1. **Turbo C/C++ Setup**: Ensure Turbo C/C++ is installed on your system. You can download it from [Turbo C++ official site](https://turbocpp.com) or use an existing installation.
2. **Graphics Library**: Verify that the BGI graphics library is available in your Turbo C/C++ installation.
3. **Download Source Code**: Copy the provided source code into your Turbo C/C++ IDE.

## Compilation
- Open the source code in the Turbo C/C++ environment.
- Compile the code using the "Compile" option.
- If any errors occur, make sure all header files (`graphics.h`, `dos.h`, `conio.h`, etc.) are properly included in your Turbo C/C++ directories.

## Usage
1. **Start the Game**: Run the compiled executable. The game will start with a menu screen.
2. **Game Controls**:
   - `W/A/S/D`: Move Pacman up/left/down/right.
   - `ESC`: Pause the game.
   - `SPACEBAR`: Start a new game (when applicable).
3. **Objective**: Navigate Pacman through the maze, eat all pellets, and avoid the ghosts. Eating all pellets wins the game. Getting caught by a ghost three times results in a game over.

## Features
- **Dynamic Ghosts**: Three ghosts with unique movement patterns.
- **Difficulty Levels**: Select different game speeds for varied difficulty.
- **Scoring System**: Score points by eating pellets.
- **Sound Effects**: Simple sound effects using the PC speaker.

## Known Issues and Troubleshooting
- **Graphics Errors**: Make sure your system supports BGI graphics and the `graphics.h` path is correctly configured.
- **Sound Issues**: The PC speaker is used for sound effects. If you encounter issues, check your speaker settings.
- **Performance**: The game may run differently on various systems. Adjust the difficulty setting if the game runs too fast or slow.

## License
This project is open-source. You are free to use, modify, and distribute it as per your needs. Credit to the original creator is appreciated.

---
Enjoy the nostalgic journey back to classic arcade gaming with this Turbo C/C++ implementation of Pacman!
