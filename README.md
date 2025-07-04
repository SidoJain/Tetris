# Tetris

**Tetris** is a fully functional, retro-style clone of the classic Tetris game built using Python and Pygame. This version supports scoring, falling block mechanics, line clearing, high score tracking, and an intuitive interface.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Running the Game](#running-the-game)
- [Gameplay](#gameplay)
- [Controls](#controls)
- [License](#license)

---

## Features

- All 7 classic Tetris shapes (S, Z, I, O, J, L, T)
- Falling speed increases as the game progresses
- Score increases for every cleared row
- Local high score tracking via `Scores.txt`
- "Next piece" preview panel
- Game over screen with restart

---

## Tech Stack

- **Language:** Python 3
- **Library:** [Pygame](https://www.pygame.org/) `v2.6.0`

---

## Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/SidoJain/Tetris.git
cd Tetris
```

2. Install dependencies using pip:

```bash
pip install -r requirements.txt
```

### Running the Game

Run the main game script:

```bash
python Main.py
```

## Gameplay

- Blocks (tetrominoes) fall from the top.
- Arrange them to fill horizontal lines.
- Full lines are cleared and score is updated.
- If the stack reaches the top, the game ends.

## Controls

- `←` / `→`: Move block left/right
- `↓`: Speed up fall
- `↑`: Rotate block
- `Q`: Quit

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).