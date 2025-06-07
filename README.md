# AI Puzzle Solver — Greedy Best-First Search

This project implements an AI agent to solve the classic **puzzle problem** using the **Greedy Best-First Search** algorithm guided by the **Manhattan distance heuristic**.

The implementation is done in **Python**, using `NumPy` for grid state representation and `heapq` for priority queue management.

---

## Problem Overview

The **puzzle** consists of a 3x3 grid with eight numbered tiles and one blank space. The objective is to reach the goal configuration by sliding tiles into the blank space.

**Example:**

Initial State:

1 2 3
4 6 5
7   8

Goal State:

1 2 3
4 5 6
7 8

## Features

- Implements the **Greedy Best-First Search** algorithm.
- Uses the **Manhattan distance** as a heuristic.
- Step-by-step solution path is printed to the console.
- Designed with clean, modular class-based code.
