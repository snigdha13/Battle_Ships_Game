# Battle_Ships_Game
Mini project - Battle ships game using core java
This project would be a great opportunity to strengthen understanding of arrays and nested loops.
First, I'd create a 10 by 10 grid as the ocean map. This grid will serve as the battlefield for both the player and the computer. It would be a two-dimensional array, representing rows and columns.
Ships Placement: Next, I'd implement a feature to allow the player to place their 5 ships on the grid. This would involve validating the input for ship placement to ensure they don't overlap or go out of bounds. Randomly deploying the computer's ships on its side of the grid would also be necessary.
Game Loop: I'd create a game loop that would alternate between the player's and computer's turns. Within this loop, both the player and the computer would input coordinates to "attack" the opponent's grid.
Attacks and Ship Sinking: I had implemented the logic for checking if an attack hits one of the ships or misses. When a ship is hit, I'd reduce its count, and it would be considered sunk.
Win Condition: The game loop would continue until either the player or the computer has no ships left. At that point, the game would end, and a winner would be declared.
