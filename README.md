# Treasuregame
This is my first project using c++ where we had to make a terrain geneator that was 'infinite' and have a compass. 
I created a treasure chest game where a player, a chest, and a key get spawned on a map using a 2d array.
The player can move across the map in 4 directions (NESW) and once it hits the edge of the map in can reappear on the opposite side. This is how I implemented the idea
of the map being infinite. Each turn the player moves, it gives you the distance to the treasure using pythagoras, and once the treasure is found the game ends.
