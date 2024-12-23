# GuideMe

## Overview
GuideMe is a graphical application designed to help users visualize and explore available transportation options between cities on a map. The project utilizes SFML (Simple and Fast Multimedia Library) to create an interactive GUI that represents cities as nodes and transportation routes as edges. The application supports multiple pathfinding algorithms, including BFS, DFS, and Dijkstra, to assist users in selecting optimal routes based on their needs, such as minimizing cost or distance.

---
**to run GUI clone from sfml branch**

## Features

1. **Interactive Visualization**
   - Cities are represented as nodes on the map.
   - Routes between cities are displayed as edges connecting the nodes.
   - Visual feedback for user actions, such as selecting source and destination cities.

2. **Pathfinding Algorithms**
   - **BFS (Breadth-First Search)**: Explores all paths level by level to find the shortest path in terms of the number of edges.
   - **DFS (Depth-First Search)**: Traverses paths deeply to find all potential routes.
   - **Dijkstra's Algorithm**: Finds the shortest path based on weights (e.g., travel costs or distances).

3. **All Paths Computation**
   - Users can calculate all possible paths between two cities within a specified budget.
   - Displays detailed information about each path, including cost and travel mode.

4. **Dynamic Node Interaction**
   - Cities repel each other dynamically to prevent overlapping nodes for better visualization.
   - Nodes can be clicked to set the source or destination city.

5. **Custom Background and City Icons**
   - Background images and city-specific icons for an enhanced user experience.

6. **Keyboard Controls**
   - Press **B**: Execute BFS.
   - Press **D**: Execute DFS.
   - Press **Z**: Execute Dijkstra’s Algorithm.
   - Press **Q**: Calculate all paths.
   - Press **Escape**: Exit the application.

---

## Usage Instructions
- user name : user
- password : user 
1. **Set Source and Destination**
   - Left-click on a city node to set it as the source.
   - Right-click on a city node to set it as the destination.

2. **Execute Algorithms**
   - Press **B** for BFS.
   - Press **D** for DFS.
   - Press **Z** for Dijkstra’s Algorithm.
   - Press **Q** to calculate all paths within a budget.

3. **Visualization Controls**
   - Observe node animations and path highlights during traversal.

4. **Exit**
   - Press **Escape** to close the application.



---

## BFS Visual Example Run 


https://github.com/user-attachments/assets/d4d80eb2-9df6-4cb0-8012-153ea3e19ece




