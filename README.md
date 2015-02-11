# World War Z++
**Problem**: Many things, such as death and taxes, are inevitable. Another thing that's inevitable, in the scope of this problem, is the Zombie Apocalypse. You are the lone survivor (good job, go you!), but you're stuck on the top floor of a warehouse (a vertical maze) full of the brain munching monsters. That sucks.

**Rules**: 
 Build a function that runs through the maze, that takes into account not just walls, but also zombies.
 Luckily, zombies can't move (they're hungry, you don't like moving when you're hungry either, don't judge).

**Moving**: 
* You can move one space in any direction (that you are able) during a step.
* You can move through gaps in the floor (" ").
* You will start at the S position and finish at the F position.
* You cannot move through walls ("|"), as they are solid.* If you hit a wall, or a Zombie, you will need to switch directions on the next step.

 NOTE: You do not need to create a function to go up floors, but you are welcome to give it a shot for extra credit.

**Requirements**:
 Your function should take in a maze grid, which is an array of strings.

 Example Maze Grid:
```javascript
var mazeGrid = 
["         S  ",
"|________ __|",
"| _________Z|", 
"| Z_________|",
"| |_____Z___|",
"| _________Z|",
"|__ __Z_____|",
"|_____ ___Z_|",
"| |__| _____|",
"| ________Z_|",
" F           "]```
