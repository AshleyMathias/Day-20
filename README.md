# Day-20
Snake Game 🐍
A classic Snake game built using Python's turtle module! Guide the snake around the screen, avoiding obstacles and growing as you play.

Features 🌟
Interactive Gameplay: Control the snake using arrow keys.
Smooth Animation: The game runs at a consistent frame rate with smooth movement.
Classic Snake Mechanics: The snake grows as it moves, and the game ends if it collides with itself (to be implemented).
Prerequisites 📋
Python 3.x installed on your system.
The turtle module (pre-installed with Python).
How to Play 🚀
Run the program.
Use the arrow keys to control the snake's movement:
Up Arrow: Move up.
Down Arrow: Move down.
Left Arrow: Move left.
Right Arrow: Move right.
Try to maneuver the snake without colliding with itself or the boundaries (future enhancement).
Code Overview 🔄
1. Main Game Loop:
Sets up the screen with a black background and title.
Initializes the snake and listens for keypress events.
Continuously updates the screen and moves the snake in the game loop.
2. Snake Class:
Attributes:
segments: List to hold the snake's body parts.
head: Refers to the first segment of the snake.
Methods:
create_snake(): Initializes the snake with three segments at the starting position.
move(): Moves each segment of the snake forward by updating coordinates.
up(), down(), left(), right(): Changes the snake's direction while preventing reverse movement.
