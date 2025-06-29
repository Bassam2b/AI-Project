AI Maze Solver: Search Algorithms and Q-Learning

This project implements an intelligent agent that navigates a 47×47 maze using a combination of search algorithms and reinforcement learning. The agent learns to reach a goal while optimizing the path based on distance and reward functions.

Features

- Supports a 47x47 custom maze environment.
- Implements a transition model for navigating in four directions: North, South, East, and West. Boundary checks and goal validation on each move.

Search Algorithms Implemented

1. Uninformed Search
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Iterative Deepening Search (IDS)
- Uniform Cost Search (UCS)

2. Informed Search (Heuristics)
- Greedy Best-First Search using:
  - Manhattan Distance & Euclidean Distance
- Search Algorithm

3. Local Search Techniques**
- Hill Climbing, Simulated Annealing, and Genetic Algorithm

4. Q-Learning (Reinforcement Learning)
- Epsilon-greedy action selection
- Reward shaping based on proximity to goal and penalties
- Q-value update rule using temporal difference (TD)
- Adaptive epsilon decay
- Goal detection and path optimization

Q-Learning Reward Strategy

- Step penalty: -1
- Staying in the same state: -10
- Returning to start: -5
- Moving closer to goal: +10
- Reaching goal: +1000
- Step penalty scaled by number of steps

Output
Console print of episode number, steps taken, total reward, and epsilon

Visualization of pathfinding strategies and optimal path

Q-table generation for policy analysis
