# Pacman Game

A classic Pacman game implementation in C++ using SFML library. This project was developed as part of an Object-Oriented Programming course at Klaipeda University.

## Features

- Classic Pacman gameplay mechanics
- Multiple levels with increasing difficulty
- Ghost AI with different behaviors
- Sound effects and background music
- Score tracking system
- Lives system
- Power pellets and energizers

## Requirements

- C++ compiler (g++ or clang++)
- CMake (version 3.0 or higher)
- SFML library (version 2.5 or higher)

## Building the Project

1. Clone the repository:
```bash
git clone https://github.com/logeshjankeeram/OOP-GAME.git
cd OOP-GAME
```

2. Create a build directory and navigate to it:
```bash
mkdir build
cd build
```

3. Generate build files using CMake:
```bash
cmake ..
```

4. Build the project:
```bash
make
```

## Running the Game

After building, you can run the game from the build directory:
```bash
./MazeRunner
```

## Controls

- Arrow keys: Move Pacman
- ESC: Pause game
- Space: Start game
- R: Restart level

## Project Structure

- `Source/`: Contains all source code files
  - `Headers/`: Header files
  - `Resources/`: Game resources (images, sounds, levels)
- `CMakeLists.txt`: Build configuration
- `Resources/`: Game assets

## Credits

- Developed by: Logesh Jankeeram
- Course: Object-Oriented Programming
- University: Klaipeda University

## License

This project is open source and available under the MIT License. 