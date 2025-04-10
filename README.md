# Labyrinth

This is a terminal-based labyrinth puzzle game written in **MIPS Assembly**, developed as part of a university project at **Technical University of Crete (TUC)**. The objective is simple: guide your player through a maze and reach the goal symbol `@` — but you’ll need to avoid walls, plan your moves, or use the built-in solver.

---

## 🎓 Project Info

- **Course**: Digital Computers
- **Institution**: Technical University of Crete (TUC)
- **Department**: School of Electrical and Computer Engineering
- **Semester**: Fall 2018
- **Project Type**: Individual assignment
- **Language**: MIPS Assembly
- **Platform**: Linux

---

## 🎮 Game Description

This program simulates a player navigating a maze displayed with ASCII characters. You use keyboard inputs to move in four directions. Walls (`I`) block movement, and the goal is to reach the end marked by `@`. You can also press `E` to auto-solve the maze and see the optimal path.

---

## ✨ Features

- Terminal-based UI with ASCII maze rendering
- Movement controls:
  - `W` → Up
  - `S` → Down
  - `A` → Left
  - `D` → Right
  - `E` → Auto-solve path
- Win detection when reaching `@`
- Invalid moves are blocked and feedback is given
- Basic pathfinding using a recursive solver

---

## 🛠 How to Build & Run (Linux)

### Prerequisites

- Linux system required (personally used a VM for Linux)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/ISeferli/Labyrinth
   ```

2. **Run the game**
    ```bash
    spim -file Labyrinth.asm
    ```

3. **Follow on-screen instructions:**
    ```mathematica
    W - Up
    S - Down
    A - Left
    D - Right
    E - Auto-solve
    ```

