# Degrees of Separation

This project finds the shortest path between two actors based on their shared film appearances. It uses **Breadth-First Search (BFS)** to calculate degrees of separation in a graph of people and movies.


---

## Project Overview

Given a dataset of actors and movies, the program:
- Builds a graph where nodes are **actors**, and edges represent **shared movies**.
- Uses **BFS** to find the shortest path between two actors.
- Outputs the sequence of actors and the movies that link them.

This models the concept of **"Six Degrees of Kevin Bacon"**, where any actor can be connected to another through shared film roles.

---

## Concepts Used

- Breadth-First Search (BFS)
- Graph Representation
- Queue Data Structures
- Pathfinding Algorithms
- Data Parsing and Cleaning (CSV files)

---


---

## ▶️ How to Run

With python3 installed in computer run code below:

```bash
python3 degrees.py
```

With python installed in computer run code below:

```bash
python degrees.py
```

## Example

Name: Emma Watson  
Name: Daniel Radcliffe  

1 degrees of separation.

Emma Watson and Daniel Radcliffe starred in:
Harry Potter and the Prisoner of Azkaban (2004)



