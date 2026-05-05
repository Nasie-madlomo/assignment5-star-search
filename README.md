# A* Search – Truck Logistics Route Optimisation

##  Overview

This project implements the **A* search algorithm** to find the optimal route for a logistics truck travelling from **Disaneng** to **Coligny** in the North West province. The graph represents towns (nodes) and road distances (edges), with heuristic values based on "traffic per city" to guide the search.

## Problem Statement

A logistics company needs to find the shortest (least cost) path between two towns, considering real road distances. The A* algorithm is used because it combines the actual cost from the start (`g(n)`) with an estimated cost to the goal (`h(n)`) — making it more efficient than uninformed search methods.

##  Files in this Repository

| File | Description |
|------|-------------|
| `A_star_search.py` | Main Python script containing the A* algorithm, graph, weights, and heuristic. |
| `A_star_search_testcase.py` |  Test script for verifying components. |
| `screenshot_output.png` | Screenshot of the terminal showing the successful output. |

## Graph Representation

- **Nodes** : Towns (Disaneng, Mahikeng, Coligny, etc.)
- **Edges** : Roads with distances in kilometres
- **Heuristic** : Traffic values from the assignment table (estimated cost to Coligny)

##  Results

After running the A* algorithm, the optimal route found was:
**Total cost** : 110 km

The output also shows the order in which nodes were visited, confirming that the algorithm explored efficiently towards the goal.
