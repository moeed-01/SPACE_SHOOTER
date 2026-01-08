The Space Shooter Game is a 2D arcade-style game developed in C++. The player controls a spaceship to destroy enemy ships while avoiding collisions and enemy fire. The game includes progressive difficulty, real-time scoring, and file-based high score management using a graphics library such as SFML or graphics.h.

Features
Game Levels:
Enemies appear in waves with increasing difficulty.

Player Controls:
Movement using arrow keys or WASD.
Shooting using the spacebar.
Collision with enemies or projectiles reduces player life.

Scoring System:
Points awarded for destroying enemies.
Bonus points for consecutive kills.
Score displayed in real time.

Game Interface:
Displays score, remaining lives, and game status.
Game Over screen with restart option.
Play button at game start.

Player Health:
Player starts with 3 lives.
One life lost per collision or hit.
Game ends when all lives are lost.

Data Structures Used:
2D arrays for enemy position and state management.
Vectors for handling player bullets.
File handling for storing and loading leaderboard data.

File Handling:
Save and load high scores.
Option to save and load game progress.
Technical Details

Language: C++

Graphics Library: SFML or graphics.h

Enemy spawning with randomized positions.

Keyboard-based real-time input handling.

Hitbox-based collision detection.

Functionality Summary

Initialize game entities and render visuals.

Handle player movement and shooting.

Detect collisions and update scores.

Increase difficulty through wave progression.

Save and load leaderboard data.
