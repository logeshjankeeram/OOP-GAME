Maze game


added the following features to the game:

Object-Oriented Design

* Apply encapsulation (use private, protected, public properly).
* Demonstrate polymorphism (e.g., virtual act() for different actor behavior).
2. SFML Integration
3. Score System
*Track the player's score in the game.
* Implement file input/output to save and load high scores using basic file handling.

Game Mechanics
* Player movement with constraints
* Enemies spawning
* Some form of interaction: avoiding
5. Collision Handling
6. Game Loop
* Keep the game running with smooth animations and framerate handling.
* Ability to restart or exit the game cleanly.
7. Visual Feedback : game flashes when player dies
* Use basic graphics and optional sound effects (bonus).
* Display score, lives, or level info on screen.
• Level system or increasing difficulty.
• Animated sprites.
• Sound effects using sf::Sound.
• Menu system or pause functionality.

## Controls

- WASD to move
- ESC: Pause game
- Enter: Start game

Note due to me running the game from mac- i coudl not test it from terminal. The game has to be package as .app to run or run directly from finder

## Project Structure
- `Source/`: Contains all source code files
  - `Headers/`: Header files
  - `Resources/`: Game resources (images, sounds, levels)
- `CMakeLists.txt`: Build configuration
- `Resources/`: Game assets