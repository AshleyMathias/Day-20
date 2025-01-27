# Day-20
Snake Game 🐍
A classic Snake game built with Python's turtle module. Navigate the snake to eat food, grow longer, and avoid walls or colliding with yourself. The game ends if you hit the wall or your own body!

Features 🌟
Snake Growth: Each time the snake eats food, it grows.
Score System: Keep track of your score and aim to achieve the highest score.
Game Over: The game ends if the snake collides with the wall or itself.
Interactive: Use arrow keys to control the snake.
Prerequisites 📋
Python 3.x installed on your system.
The turtle module (pre-installed with Python).
How to Play 🚀
Run the program.
Control the snake using the arrow keys:
Up Arrow: Move up.
Down Arrow: Move down.
Left Arrow: Move left.
Right Arrow: Move right.
Try to eat as much food as possible while avoiding walls and colliding with the snake's body.
Code Overview 🔄
1. Snake Class:
Attributes:
segments: List of the snake’s body parts.
head: The first segment, representing the snake's head.
Methods:
create_snake(): Initializes the snake with three segments.
move(): Moves each segment of the snake forward.
extend(): Adds a new segment to the snake’s body after it eats food.
up(), down(), left(), right(): Changes the direction of the snake's movement.
2. Food Class:
The food is a blue circle that randomly reappears at new positions after being eaten by the snake.
3. Scoreboard Class:
Displays the player's score at the top of the screen.
Updates the score when the snake eats food.
Displays "GAME OVER" when the game ends.
How the Game Works ⚙️
Movement: The snake moves forward by one segment at a time.
Eating Food: Every time the snake eats food, it grows, and the score increases.
Game Over: The game ends if the snake hits a wall or collides with its own body. The final score is displayed after the game ends.
