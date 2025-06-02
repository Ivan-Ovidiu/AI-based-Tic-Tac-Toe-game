# Tic-Tac-Toe AI Game

A Tic-Tac-Toe game with artificial intelligence using Minimax and Alpha-Beta pruning algorithms.

## Features

- Tic-Tac-Toe game with graphical interface
- AI that plays optimally using Minimax or Alpha-Beta algorithms
- Choose to play as X or O
- AI calculates the best possible move

## How to Run

### Requirements
```bash
pip install pygame
```

### Required Images
Place in project folder:
- `ics.png` - for X symbol
- `zero.png` - for O symbol

### Run the Game
```bash
python main.py
```

## How to Play

1. Choose algorithm: 1 for Minimax, 2 for Alpha-Beta
2. Choose your symbol: x or 0
3. Click on empty cells to place your symbol
4. AI makes its move automatically
5. Win by getting three in a row

## Algorithms

### Minimax
- Calculates all possible moves
- Chooses the move that maximizes winning chances

### Alpha-Beta
- Optimized version of Minimax
- Faster because it eliminates unnecessary search branches

## Settings

You can modify in code:
```python
ADANCIME_MAX = 6    # How deep AI thinks ahead
NR_COLOANE = 3      # Board size (3x3)
```

## Code Structure

- `InfoJoc` - manages the board and game rules
- `Stare` - represents a game state for AI
- `min_max()` - Minimax algorithm
- `alpha_beta()` - Alpha-Beta algorithm with optimizations


