# Clover Minesweeper 3D - Unique Problems Edition

## Overview

Clover Minesweeper 3D is a fully-featured, visually enhanced minesweeper game designed in OpenGL using Python. When a mine is triggered, a math minigame appears with a unique arithmetic problem. Each problem is guaranteed never to repeat during your session. The game features colorful 3D cubes, animated clouds, a modern UI, and precision controls.

## Features

- 3D interactive minesweeper grid with multi-layer support
- Mini-game math popups with **non-repeating unique problems**
- Beautiful environment: animated clouds, grass, and colorful cubes
- Transparent background UI overlays for clear readability in minigame
- ULTIMATE mouse precision: 3-algorithm coordinate mapping
- Smooth animated camera controls and transitions
- Game stats, controls, and helpful visual cues embedded in UI
- Multi-layer progression, scanner, hack mode, flagging

## Controls

- **WASD**: Move selection (skips revealed cubes)
- **Mouse**: Click cubes (precision selection)
- **Space**: Reveal selected cube (triggers minigame on mine)
- **F**: Flag/unflag selected cube
- **X**: Use scanner (reveals 3x3 safe region)
- **H**: Toggle hack mode (show/hide mines)
- **V**: Toggle camera view (first/third person)
- **Tab**: Cycle through unrevealed cubes
- **Arrow Keys**: Move camera
- **R**: Reset game

## Minigame Rules

- When a mine is triggered, a math problem appears in a semi-transparent popup.
- Problems are addition (`+`), subtraction (`-`), or multiplication (`*`) using numbers 1-25.
- No problem will ever repeat until all possible problems are exhausted.
- Subtraction is always non-negative.
- You must solve the problem within the time limit to defuse the mine.
- If you fail or answer incorrectly, the mine detonates, resulting in Game Over.

## Installation

### Prerequisites

- Python 3.8+
- pip

### How to Run

1. Install dependencies from `requirements.txt`:
2. Run the game:

## Files

- `clover-minesweeper-UNIQUE.py`: Main game executable (unique problems, best visuals)
- `requirements.txt`: Libraries needed to run the game


## Tips

- Ensure graphics drivers are updated for best OpenGL performance.
- Use keyboard controls for swift gameplay and camera movement.
- Enjoy randomized, never-repeating math challenges as you play!

---

# Enjoy Clover Minesweeper 3D!  
