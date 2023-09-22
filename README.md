# maze-solver
This Python script uses the `curses` library to visualize and solve a maze. It finds a path from the start point (O) to the end point (X) using a breadth-first search algorithm.

## Prerequisites

- Python 3.x
- The `curses` library is used for the console-based visualization. No additional installation is required, as `curses` is part of the Python standard library.

## Usage

1. Ensure you have Python 3.x installed on your system(Windows,MacOS or Linux).
2. Fork or download the repository.
3. Open your terminal or command prompt and navigate to the directory containing the Python script.
4. Run the script using the following command:

   ```bash
   python script_name.py
Replace script_name.py with the actual name of the Python script.

The script will display the maze and visualize the path-finding process from the start (O) to the end (X). Once the path is found, the maze will be displayed with the path highlighted in red. Press any key to exit.
Maze Representation
The maze is represented as a 2D list, where:

"#" represents walls or obstacles.
"O" represents the starting point.
"X" represents the endpoint.
" " (space) represents open paths.

maze = [
    ["#", "O", "#", "#", "#", "#", "#", "#", "#"],
    ["#", " ", " ", " ", " ", " ", " ", " ", "#"],
    ["#", " ", "#", "#", " ", "#", "#", " ", "#"],
    ["#", " ", "#", " ", " ", " ", "#", " ", "#"],
    ["#", " ", "#", " ", "#", " ", "#", " ", "#"],
    ["#", " ", "#", " ", "#", " ", "#", " ", "#"],
    ["#", " ", "#", " ", "#", " ", "#", "#", "#"],
    ["#", " ", " ", " ", " ", " ", " ", " ", "#"],
    ["#", "#", "#", "#", "#", "#", "#", "X", "#"]
]
The maze above was the sample maze used for execution. You can edit the maze in the file and would still get the expected results. I ensured this as I tested severally with different mazes to ensure the program would always work fine. No values are hard coded into the algortithm, and I made use of functions to acquire values for the start and end points.

##Algorithm
The script uses a breadth-first search algorithm to find the shortest path from the start to the end while visualizing the exploration process.

##Credits
This code was created as an educational example and is inspired by breadth-first search coding interview algorithm question, and a TechWithTim Youtube tutorial on creating terminal applications with Curses.

Feel free to modify and use this code for your projects or educational purposes.

