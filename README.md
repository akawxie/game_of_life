# Conway's Game of Life

An interactive web implementation of Conway's Game of Life using HTML, CSS, and JavaScript.

## Features

- Interactive grid where you can toggle cells by clicking
- Controls to start/stop the simulation, take single steps, and clear/randomize the grid
- Speed control to adjust simulation speed
- Predefined patterns: Glider, Pulsar, Glider Gun, and Spaceship
- Mobile-friendly with touch support for drawing on the grid
- Statistics tracking (generation count, population, elapsed time)

## How to Play

1. Click on the grid to toggle cells between alive and dead states
2. Use the control buttons to:
   - Start/Stop the simulation
   - Take a single step
   - Clear the grid
   - Generate a random pattern
3. Adjust the speed using the slider
4. Select predefined patterns from the patterns panel

## Rules of Conway's Game of Life

1. Any live cell with fewer than two live neighbors dies (underpopulation)
2. Any live cell with two or three live neighbors lives
3. Any live cell with more than three live neighbors dies (overpopulation)
4. Any dead cell with exactly three live neighbors becomes alive (reproduction)

## Live Demo

The game is deployed at: https://akawxie.github.io/game_of_life/ 