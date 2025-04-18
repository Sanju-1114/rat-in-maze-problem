# Rat in a Maze Problem

This repository contains a C++ solution to the classic **Rat in a Maze** problem. The algorithm finds all possible paths from the top-left corner to the bottom-right corner of a maze represented by a 2D grid.

## 🧠 Problem Statement

Given an `N x N` maze with some cells blocked, find all the paths from the top-left cell `(0,0)` to the bottom-right cell `(N-1,N-1)`, moving only in four directions — up, down, left, and right. You cannot visit any cell more than once in a single path, and you can only move through cells that contain a `1`.

## 🚀 Features

- Recursive backtracking algorithm
- Path tracking with directions (`U`, `D`, `L`, `R`)
- Handles multiple paths
- Easy to understand and modify

## 🛠️ Usage

### 1. Clone the repository:
```bash
git clone https://github.com/Sanju-1114/rat-in-maze-problem.git

```

### 2.  Compile and run:
```bash
    g++ ratInAMaze.cpp -o ratMaze
    ./ratMaze
```

## 🧩 Example Maze

The maze used in this program looks like this:
    1 0 0 0
    1 1 0 1
    1 1 0 0
    0 1 1 1

`1` - Open path  
`0` - Blocked cell  

## 🧪 How it works

- Starts at `(0,0)`
- Moves in valid directions and marks visited cells
- Appends direction letters (`D`, `U`, `L`, `R`) to form a path string
- Adds each valid path to a result list
- Uses backtracking to explore all possibilities

## 📁 File Structure

- `ratInAMaze.cpp` — Main implementation file




  