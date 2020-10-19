# Conway's Game of life 

Conway's Game of Life is a game invented by the British mathematician Conway around 1970. Even though it is a game, all the user can do is decide the initial placement of life, and then enjoy the changes on the screen. It's like a kaleidoscope.

Conway's Game of Life consists of very simple rules. Various shapes are produced from such simple rules. Its behavior is very complex and feels like life. The emergence of complex behavior from such simple rules is called emergence in the field of artificial life . Conway's Game of Life is a classic program in the field of artificial life.

The interesting thing about Conway's Game of Life is that there can be objects with life in the world of Conway's Game of Life. eh? Isn't there a living thing in the computer? Some people in the world don't think so. Not all organisms made of proteins that we know. The essence of life is self-replication, and it doesn't matter whether it's made of protein or software ...

Among those who studied the self-reproduction of living things in the virtual world of life games are von Neumann, who invented the principle of personal computers, and Langton, who started researching artificial life. They have actually created a self-replicating loop and succeeded in reproducing the same phenomenon as a living thing.

# Rules
The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead. Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
  
  1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
  2. Any live cell with two or three live neighbours lives on to the next generation.
  3. Any live cell with more than three live neighbours dies, as if by overcrowding.
  4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
  
  The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations.
