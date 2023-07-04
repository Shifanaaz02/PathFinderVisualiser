# OPTIPATH

This project is a visualisation of pathfinding algorithms present in many software applications. The pathfinding algorithms in this project include Breadth-first Search, Depth-first Search, Dijkstra's Algorithm and A* algorithm. Some practical uses for pathfinding algorithms include video game pathfinding, Google Maps and the internet.

## Meet the Algorithms

This application supports the following algorithms: 

**Dijkstra's Algorithm** (weighted): the father of pathfinding algorithms; guarantees the shortest path

**A* Search** (weighted): arguably the best pathfinding algorithm; uses heuristics to guarantee the shortest path much faster than Dijkstra's Algorithm

**Breath-first Search** (unweighted): a great algorithm; guarantees the shortest path

**Depth-first Search** (unweighted): a very bad algorithm for pathfinding; does not guarantee the shortest path.

## How does it works

Initially you will be displayed with an empty 2-dimensional grid with the start and finish nodes. They are where the search starts and finishes respectively and are displayed by the person and the treasure chest icons. You can use the buttons in the navbar to create random walls and clear them. On desktop, you can also use the cursor on the empty squares/nodes and drag it to draw walls. You can also move the start and finish nodes around by clicking and dragging. Once you are happy with the grid, you can select an algorithm and start visualising!

You will see the green nodes slowly fill up the adjacent nodes in the grid - this is the searching part. Once the green nodes find the finish node, then the yellow nodes will display the path the algorithm chose to get there. Note that this is not always the shortest path for Depth-first search. It is the shortest path for some algorithms however (like Dijkstra's and Breadth-first search).

## Features

**Responsive design for the grid and components try it out on mobile, tablet and desktop!**
**Can generate random walls or draw them**
**Can drag the start and finish (on desktop)**

