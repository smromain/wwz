***World War Z++**
**Problem**: Many things, such as death and taxes, are inevitable. Another thing that's inevitable, in the scope of this problem, is the Zombie Apocalypse. You are the lone survivor (good job, go you!), but you've wandered into a labyrinth full of the brain munching monsters. That sucks.

**Rules**: 
 Build a function that runs through the maze, that takes into account not just walls, but also zombies.
 Luckily, zombies can't move (they're hungry, you don't like moving when you're hungry either, don't judge).

**Moving**: 
 You can move one space in any direction (that you are able) during a step.
 You may want to look down first during a step before trying a move in either direction. 
 If you hit a wall, or a Zombie, you will need to switch directions on the next step.

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
" F           "]```# wwz
