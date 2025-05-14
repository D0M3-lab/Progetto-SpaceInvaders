# Space Invaders Game with Sprites and Barriers
This program is a Python-based implementation of the classic Space Invaders game using the Tkinter library for the graphical interface. It features a player-controlled spaceship, enemy invaders, and destructible barriers. The game also incorporates sprites (images) for the player, enemies, and bullets. Below are the key functionalities of the game:

1. Player Controls and Movement
The player controls the spaceship using the left and right arrow keys to move horizontally.

The player can shoot bullets using the spacebar. The bullets are fired from the center of the spaceship.

2. Enemies
The game features a grid of enemy invaders that move horizontally across the screen. Once they hit the edge of the screen, they drop down and reverse direction.

Enemies periodically shoot bullets toward the player.

3. Barriers
There are destructible barriers placed near the bottom of the screen. The player can hide behind these barriers for protection, but they are gradually destroyed when hit by enemy bullets or player bullets.

4. Collision Detection
The program checks for collisions between player bullets and enemies, enemy bullets and the player, as well as between bullets and barriers.

When a bullet hits an enemy, the enemy is destroyed, and the player's score increases. Similarly, when a bullet hits a barrier, that section of the barrier is destroyed.

5. Scoring
The player earns 10 points for each enemy destroyed.

The score is displayed at the top of the screen and is updated whenever an enemy is hit.

6. Game Over and Winning
The game ends if an enemy reaches the bottom of the screen or if the player is hit by an enemy bullet. A "Game Over" screen is displayed with an option to restart.

If all enemies are defeated, a "You Win!" message is shown.

7. Restart Functionality
After the game ends, the player can restart the game by clicking the "Restart" button, which resets the game state, enemies, and score.

8. Game Mechanics
The game has a fire delay to prevent the player from shooting too rapidly.

Enemy firing is random, with a small chance that each enemy will shoot a bullet at the player during each update cycle.

9. Visual Elements
The game uses sprites for the player’s spaceship, enemies, and bullets. These images are loaded from external files (e.g., 'player.png', 'enemy.png') and resized to fit the game’s dimensions.

