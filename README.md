# PathFindingAlgorithm
This project is a Python application that uses the A* algorithm to find the shortest path between two points on a map or grid, taking into account any obstacles set by the user. The heuristic function used in this implementation is the Manhattan distance.

## Features
Interactive front-end that allows the user to visually select the starting and ending points and set obstacles between them.
A* algorithm implementation with Manhattan distance as the heuristic function to calculate the shortest path.
The application can be used in various fields such as logistics and transportation, gaming, and robotic navigation to efficiently find the shortest path in a grid-based environment.

## Requirements
1. Python 3.x
2. PyQt or Tkinter (for GUI)

## Useage
1. Clone the repository
```Terminal
git clone https://github.com/hirey-m/PathFindingAlgorithm
```
2. Install the required libraries
```Terminal
pip install pygame
```
3. Run the application
```Terminal
python main.py
```
4. Follow the instructions on the GUI to select the starting and ending points and set obstacles between them.

6. Click on the "Find Shortest Path" button to calculate the shortest path between the selected points

## Contribution
We welcome contributions to this project. If you find any bugs or have any suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)

## Screenshots

![Types of Nodes](https://raw.githubusercontent.com/manavhirey/PathFindingAlgorithm/main/pfa1.jpg)

![Types of Nodes](https://raw.githubusercontent.com/manavhirey/PathFindingAlgorithm/main/pfa2.jpg)

## Selecting the Source, Destination Nodes and setting up Obstacles Blocks
![Demo CountPages alpha](https://j.gifs.com/57lwyv.gif)

## Nodes being Visited and Traversed.
![Demo CountPages alpha](https://j.gifs.com/lRvkO5.gif)

## Visualizing the Shortest Path between the two selected Nodes
![Demo CountPages alpha](https://j.gifs.com/16YpjR.gif)
