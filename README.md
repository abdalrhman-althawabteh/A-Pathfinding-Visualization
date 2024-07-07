# A* Pathfinding Visualization

This project is an implementation of the A* pathfinding algorithm in Python, with a graphical visualization. The project is based on a tutorial by TechWithTim and demonstrates how the A* algorithm finds the shortest path between two points on a grid.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgements](#acknowledgements)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/abdalrhman-althawabteh/A-Pathfinding-Visualization.git
    ```
2. Navigate to the project directory:
    ```bash
    cd astar-pathfinding-visualization
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script:
    ```bash
    python main.py
    ```
2. A window will open displaying the grid. Use the mouse to create the start and end points, as well as obstacles. Then press the spacebar to start the pathfinding visualization.

## Features

- Visualization of the A* pathfinding algorithm.
- Interactive grid where users can set start and end points and place obstacles.
- Clear visualization of open and closed sets during the algorithm's execution.
- Display of the final path from start to end point.

## Acknowledgements

This project is based on a tutorial by TechWithTim. You can watch the original tutorial [here](https://www.youtube.com/watch?v=JtiK0DOeI4A&list=PLzMcBGfZo4-kNEPqSOaglnUZz3D2R4OzY&index=3&ab_channel=TechWithTim).
