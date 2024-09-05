Game Of Life implementation in Java

Summary
The application takes an initial state or generates a random initial state, then proceeds to calculate the next state.

I have made the prgram and added the testing using junit. 

Basic Rules
Any live cell with fewer than two live neighbours dies (referred to as underpopulation or exposure[1]).
Any live cell with more than three live neighbours dies (referred to as overpopulation or overcrowding).
Any live cell with two or three live neighbours lives, unchanged, to the next generation.
Any dead cell with exactly three live neighbours will come to life.
