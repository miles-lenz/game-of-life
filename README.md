# Conways Game of Life

This is my implementation of Conway's game of life using Python and the Pygame module.

## Installation
1. Clone this repository
```
git clone https://github.com/miles-lenz/game-of-life.git
```
2. Create and activate a virtual environment (optional)
```
python -m venv .venv
.venv\Scripts\activate
```
3. Install the required packages
```
pip install -r requirements.txt
```

## Usage

Run the _main.py_ file. In the _config.json_ file, you can choose some basic settings to modify the game. Here is a quick explanation for each entry:
- cell-size (integer): Changes the cell-size. (__Warning:__ This number shouldn't be bigger than your screen size because this will raise an error or too low due to possible lags).
- cell-color-alive (rgb-values): The color of a cell when it is alive.
- cell-color-dead (rgb-values): The color of a cell when it is dead.
- bg-color (rgb-values): The color of the background behind the grid.

(Depending on the grid size, it is possible that you won't be able to see this color)

When you initially start the file you will be in __draw mode__. This means you can draw your own starting grid layout and then start the game. The following shortcuts can be used to navigate through the game:
- Left mouse button: Change the cell state to 'alive' (only in draw mode).
- Right mouse button: Change the cell state to 'dead' (only in draw mode).
- CTRL + C: Exit the program at all times.
- CTRL + S: Start the simulation when in draw mode.
- CTRL + R: Reset the simulation when simulation is running.

## Ideas for Improvement

Perhaps I will add an _.exe_ file, so everyone can try it out.
