# Water Jug Problem Solver (AI)

## 🧠 Problem Statement
The Water Jug Problem involves two jugs with fixed capacities and no measurement markings. The objective is to measure an exact amount of water using permitted operations such as filling, emptying, and pouring water between the jugs.

In this project:
- Jug 1 capacity = 4 liters  
- Jug 2 capacity = 3 liters  
- Target amount = 2 liters  

## 🚀 Approach
The solution uses a **state space search** approach.

- Each state represents the current water levels in both jugs.
- The program explores all valid operations:
  - Fill a jug
  - Empty a jug
  - Pour water between jugs
- Previously visited states are tracked to prevent repetition and infinite loops.
- The search continues until the target amount is obtained.

## 🧩 Concepts Used
- Artificial Intelligence Problem Solving  
- State Space Representation  
- Depth-First Search (DFS)  
- Recursion & Backtracking  
- Graph Traversal  
- Cycle Detection (visited states)

## 🎯 Applications
The Water Jug Problem demonstrates AI search techniques used in:

- resource allocation and planning  
- robotics and automated systems  
- puzzle solving algorithms  
- decision-making systems  
- process optimization and fluid distribution problems  

## 📜 License
This project is open-source and free to use.


Another method for implementing Water-Jug Problem:
This program simulates the classic Water Jug Problem, a well-known Artificial Intelligence problem used to demonstrate state-space search and problem-solving techniques. The user applies numbered rules to perform valid operations on two jugs and continues until the goal state of measuring exactly 2 liters is reached.

⚙️ Rules Implemented in the Program

The program allows the user to choose rule numbers to perform operations:

1.Fill Jug X → Fill jug X to its maximum capacity (4 liters).

2.Fill Jug Y → Fill jug Y to its maximum capacity (3 liters).

3.Empty Jug X → Completely empty jug X.

4.Empty Jug Y → Completely empty jug Y.

5.Pour Y → X (until X is full) → Transfer water from jug Y to jug X until X becomes full or Y becomes empty.

6.Pour X → Y (until Y is full) → Transfer water from jug X to jug Y until Y becomes full or X becomes empty.

7.Pour Y → X (when total fits in X) → Pour all water from jug Y into jug X if it does not overflow.

8.Pour X → Y (when total fits in Y) → Pour all water from jug X into jug Y if it does not overflow.

After each operation, the program displays the current water levels in both jugs. When jug X contains exactly 2 liters, the program declares the goal state and stops.
