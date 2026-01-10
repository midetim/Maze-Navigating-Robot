# Maze-Navigating Robot (HCS12 Assembly)

## Overview
This project implements an **autonomous maze-navigating robot** using **HCS12 assembly language** with a **reinforcement-learning–inspired approach**. Rather than following a fixed path, the robot improves its navigation over time by learning from mistakes and updating its decisions when obstacles or dead ends are encountered.

The goal is reliable maze traversal with successful return to the start once the correct path is learned.

---

## Learning-Based Navigation Approach
The robot uses a **trial-and-error strategy** similar to reinforcement learning:

- Explores the maze by making decisions at intersections  
- Receives negative feedback when a dead end or obstacle is detected  
- Reverses direction and updates its stored decision for that intersection  
- Reuses successful decisions to avoid repeated failures  
- Gradually converges on an optimal path through the maze  
- Reuses the learned path to return without errors  

---

## Demonstration Video available below:

<p align="center">
  <a href="https://www.youtube.com/watch?v=qHdcZRrK16A">
    <img
      src="https://github.com/user-attachments/assets/6d47b9db-c9d2-4272-9859-9b2a37fa31e8"
      alt="Maze Navigating Robot Demo"
      width="900"
    />
  </a>
</p>











