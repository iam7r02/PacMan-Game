# PacMan-Game

I wrote Java code for PacMan game.
This game is really simple. Just avoiding ghosts and eating all food. that's all.

I defined the locations of walls, food, ghosts, and Pacman using a text based tilemap.
Pressing arrow keys can change pacman's movement direction and its image.
When pacman eats food, 10 points are added to the score. If all food is eaten, you win.
But if pacman touches a ghost, it loses one life. You have 3 lives. when lives reach zero, the game is over and resets.
A cherry spawns at random intervals on a food spot. eating it gives 100 points. It disappears automatically after 5 seconds.
If pacman or ghost collides with wall, the movement will be canceled. You can't pass through a wall. if ghost hits a wall, it randomly chooses a new direction to keep moving.
If pacman enters the open tunnel, it teleports to the opposite side of screen.
You can see current score and remaining lives at the top of the screen. and you can see win or game over message when the game ends.

Thank you for reading this.
