# Demo

<iframe width="560" height="315" src="https://www.youtube.com/embed/39H-E1_DKsw" frameborder="0" allowfullscreen></iframe>

# Nim AI Game

This Python project implements a game of Nim along with an AI player that uses Q-learning to learn and play the game effectively. The game involves removing items from piles, and the player who removes the last item loses.

## How to Play

1. Clone the repository:

   ```bash
   git clone https://github.com/AKKI0511/Nim-Game-AI.git
   cd Nim-Game-AI
   ```

2. Run the game:

   ```bash
   python play.py
   ```

   Follow the on-screen instructions to play against the AI.

## Game Rules

- Each game board has several piles of items (initially `[1, 3, 5, 7]`).
- Players take turns removing items from one pile on their turn.
- The player who removes the last item loses the game.

## Classes

### `Nim`

- Represents the Nim game.
- Tracks game state, player turns, and the winner.
- Provides methods for making moves and checking available actions.

### `NimAI`

- Implements an AI player using Q-learning.
- Learns to play the game effectively by updating Q-values based on rewards.
- Chooses actions strategically based on learned Q-values.

## Functions

- `train(n)`: Train the AI by playing `n` games against itself.
- `play(ai, human_player=None)`: Play a game against the AI as a human player.

## Acknowledgements

This project uses Q-learning, a popular reinforcement learning technique, to train the AI for playing Nim effectively.

---
