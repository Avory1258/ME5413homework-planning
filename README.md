# Path Planning Algorithms

This repository contains implementations of various path planning algorithms and their application to solve open and closed Traveling Salesperson Problems.

## Overview

This project implements and compares different path planning algorithms in a grid-based environment. The algorithms are applied to two main tasks:

- **Finding the optimal path from a starting point to visit all locations (Open TSP)**
- **Finding the optimal tour that visits all locations and returns to the start (Classic TSP)**

## Algorithms Implemented

### Path Planning Algorithms
- **A* Algorithm**: Balanced approach using both actual path cost and heuristic estimate.
- **Dijkstra's Algorithm**: Guarantees optimal path by considering only path cost.
- **Greedy Best First Search**: Fast but suboptimal approach using only heuristic estimate.

### TSP Solving Methods
- **Brute Force**: Evaluates all possible permutations to find the globally optimal solution.
- **Nearest Neighbor**: Greedy approach that always selects the closest unvisited location.

## Dependencies

- `numpy`
- `matplotlib`
- `imageio`
- `time`
- `heapq`
- `itertools`

To install the required packages:

```bash
pip install numpy matplotlib imageio
```

## Usage
Clone the repository:
```
git clone https://github.com/Avory1258/ME5413homework-planning.git
cd ME5413homework-planning
```
Open and execute the notebook file to see the algorithms in action.

## Task Descriptions
### Task 1: Open Traveling Salesperson Problem
Starting from a specified location, find the shortest path that visits all other locations (without returning to the start). Three different path planning algorithms are implemented and compared.

### Task 2: Classic Traveling Salesperson Problem
Starting from a specified location, find the shortest path that visits all other locations and returns to the starting point. Two different TSP solving methods are implemented and compared.

## Results
The implementation provides:

Visual representation of the paths found by each algorithm

Comparison of computation time, number of cells visited, and path optimality

Analysis of the strengths and weaknesses of each approach

## File Structure
src/Task_1/homework3.ipynb: Main Jupyter notebook containing all implementations and visualizations

README.md: This file

figurs: Visualizations of all the results

me5413_homework3.pdf: Report of this assignment
