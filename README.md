# Connect 4 Bot

A Connect 4 game-playing agent that uses **Monte Carlo Tree Search (MCTS)** to compete against a human player. The bot simulates thousands of possible game continuations to choose the most promising move each turn.

---

## Features

- Interactive Connect 4 game in the terminal
- Bot uses **Monte Carlo Tree Search** to plan ahead
- Includes performance analysis of MCTS runtimes
- Modular structure for easy experimentation

---

## Core Algorithm

The bot uses **Monte Carlo Tree Search (MCTS)**, a popular algorithm for decision-making in discrete, stochastic environments like board games. The agent balances **exploration** and **exploitation** using UCB1, making it adaptive and efficient.

---

## Requirements

```bash
# No external packages required unless plotting
pip install matplotlib  # For runtime analysis script
