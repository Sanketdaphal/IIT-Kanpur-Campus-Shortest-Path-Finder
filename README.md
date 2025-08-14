# IIT Kanpur Campus Shortest Path Finder

A C++ implementation of **Dijkstra’s Algorithm** to find the shortest path between two locations on the IIT Kanpur campus.  
The project uses a **custom graph data structure** and leverages STL containers such as `std::vector`, `std::unordered_map`, and `std::priority_queue` for efficient data management.

---

## Features
- **Shortest Path Calculation**: Implements Dijkstra's algorithm to determine the minimum distance between two points.
- **Custom Graph Structure**: Designed for quick lookups and scalability.
- **STL Integration**: Efficient use of `vector`, `unordered_map`, and `priority_queue`.
- **User Queries**: Console-based interface for easy interaction.
- **Extensible**: Can be integrated into graphical interfaces (e.g., SFML) for visualization.

---

## How It Works
1. **Graph Creation**:  
   - Each location is represented as a node.  
   - Paths between locations are edges with associated distances.

2. **Dijkstra’s Algorithm**:  
   - Maintains a priority queue to explore the shortest distance nodes first.  
   - Updates distances to neighboring nodes when shorter paths are found.

3. **Output**:  
   - Displays the shortest distance and the exact path from the start location to the destination.

---

## Example
```text
Enter start location: Library
Enter destination: Hall 9

Shortest distance: 2.5 km
Path: Library → Computer Centre → Hall 9
