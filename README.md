# SnakeGame-C
                                                                         Snake Game in C++ Language
Overview:
This C++ program implements a simple console-based Snake game. The game uses ASCII characters for visualization and allows the player to control the movement of a snake within a bordered area. The objective is to eat food items that appear randomly on the screen to grow the snake's length and score points. The game includes features such as multiple lives, score tracking, and game over conditions.

Features:
1. Snake Movement:The snake can move up, down, left, or right based on user input (arrow keys).
Movement causes the snake's body to follow its head.
2. Food Generation:Food items ('F') appear randomly on the screen.
When the snake consumes food, its length increases by one segment.
3. Game Controls:The game can be paused and resumed by pressing any key.
Pressing 'Esc' exits the game.
4. Score and Lives:Score is calculated based on the length of the snake minus the initial length (5).
Players have three lives. Losing a life occurs when the snake hits a wall or itself.
5. Game Over Handling:When all lives are lost, the game ends, displaying the final score and offering an option to view past game records.
6. Components:Main Function: Controls game initialization, including setting up the initial snake position, board boundaries, and starting the game loop.
7. Movement Functions (Up, Down, Left, Right): Handle snake movement and body mechanics.
8. Food Function: Generates food items randomly and handles food consumption.
9. Delay Function: Provides a delay effect to control the speed of the snake's movement.
10. Score and Life Functions: Display and manage the player's score and remaining lives.
11. Boarder and Print Functions: Draw the game board, including borders and initial instructions.

Additional Features:
Loading Screen: Displays a loading animation when the game starts.
Record Function: Records player scores and allows viewing of past game records.

Dependencies:
The game uses Windows-specific header files (windows.h, conio.h) for console handling and input functions.

Future Improvements:
Implement additional levels with increasing difficulty.
Add sound effects or graphical enhancements for a better gaming experience.
This project provides a basic implementation of the classic Snake game in C++, demonstrating fundamental game programming concepts such as input handling, game loops, and console graphics.
