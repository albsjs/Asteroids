# Asteroids Game - Python
This is a Python implementation of the classic Asteroids game, built to apply and demonstrate my knowledge of Object-Oriented Programming (OOP) principles. In this project, I focused on designing and developing the game using key OOP concepts such as classes, inheritance, polymorphism, encapsulation, and abstraction to create a modular and scalable codebase.

## Overview
The game features:

- A spaceship controlled by the player.
- Asteroids of varying sizes that float across the screen.
- A shooting mechanic where the spaceship can shoot lasers to destroy asteroids.
- Collision detection between asteroids, lasers, and the spaceship.
- A simple score system based on destroyed asteroids.

## Objective
The main goal of this project was to:

- Develop a working Asteroids game.
- Utilize Object-Oriented Programming to ensure the code is well-structured, modular, and easy to maintain.
- Implement the game logic, user input handling, and visual components.

## Key OOP Concepts Used
1. Classes and Objects
Spaceship: Represents the player's spaceship with methods for movement, rotation, and firing.
Asteroid: Handles asteroid behavior, such as movement and collision detection.
Laser: Represents the lasers fired by the spaceship to destroy asteroids.
Game: Coordinates the game logic, like checking collisions, updating the game state, and rendering the screen.

2. Encapsulation
Important attributes and methods for each game object (spaceship, asteroid, laser) are encapsulated within their respective classes to promote better data management and control over the object states.

3. Inheritance
The Asteroid class has subclasses to handle different sizes and behaviors of asteroids (e.g., large, medium, small).

4. Polymorphism
Methods like update() in the Game class take advantage of polymorphism to handle objects (spaceships, asteroids, lasers) that share common behavior but might differ in implementation.

5. Abstraction
Complex game logic such as collision detection, object interactions, and movement mechanics are abstracted within their respective classes, making the code more modular and reusable.

## How to Run
Prerequisites
Python 3.x
Pygame (for game graphics and window management)

## Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/asteroids-game-python.git
cd asteroids-game-python
```

Install the required dependencies:
```bash
pip install pygame 
```

Run the game:
```bash
python asteroids_game.py
```

## Gameplay
Use the arrow keys to rotate and move the spaceship.
Press the spacebar to fire lasers.
Destroy asteroids to gain points.
Avoid colliding with asteroids to survive.

## Challenges and Learnings
Implementing collision detection and handling interactions between different game objects.
Managing game state and ensuring smooth gameplay without bugs.
Applying OOP principles in a real-world project helped reinforce my understanding and made it easier to structure complex logic.

Future Improvements
Add sound effects and background music.
Implement more advanced AI for asteroid movement.
Add power-ups and different levels to increase the game’s difficulty.
Refactor code to separate game logic from user interface for better maintainability.
