Shortest Path Optimization – Dijkstra’s Algorithm
Problem: Delivery Route Optimization

A delivery company wants the shortest path from Warehouse (A) to Store (D).

Graph edges:

A → B = 4
A → C = 2
B → C = 5
B → D = 10
C → D = 3

SOLUTION:

Step 1: Initialize Distances

Distance from A:
A = 0
B = ∞
C = ∞
D = ∞

Step 2: Relax Neighbors of A

A → B = 4
A → C = 2

Updated:
B = 4
C = 2

Step 3: Pick Smallest Unvisited Node

C = 2
Relax C → D:
2 + 3 = 5
D = 5

Step 4: Next Smallest

B = 4
Check B → D:
4 + 10 = 14 (Not better than 5)

Final Shortest Path
A → C → D

Total Cost: 5
