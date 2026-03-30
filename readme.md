# 🎮 Tic-Tac-Toe AI using Minimax

A Python-based implementation of the classic **Tic-Tac-Toe game** powered by the **Minimax Algorithm**, an AI decision-making technique used in game theory.

---

## 📌 Project Overview

This project demonstrates how artificial intelligence can be used to solve games optimally. The AI uses the **Minimax algorithm** to evaluate all possible moves and choose the best one.

- Game: Tic-Tac-Toe (3x3 grid)
- Type: Two-player zero-sum game
- AI Strategy: Minimax Algorithm

---

## 🧠 What is Minimax?

Minimax is a recursive decision-making algorithm used in **zero-sum games** like Tic-Tac-Toe, Chess, etc.

- The AI assumes:
  - It tries to **maximize** its score (+1)
  - The opponent tries to **minimize** the score (-1)
- Possible outcomes:
  - Win → +1
  - Loss → -1
  - Draw → 0

The algorithm explores all possible future game states (game tree) and selects the optimal move.

---

## 🌳 Game Tree Concept

- Each node represents a **game state**
- Each level represents a **player's turn**
- The full Tic-Tac-Toe game tree contains **549,946 nodes**

---

## ⚙️ How It Works

### Function: `minimax(state, depth, player)`

#### Parameters:
- `state` → current board configuration
- `depth` → level in the game tree
- `player` → MAX (+1) or MIN (-1)

#### Logic:
1. If game is over:
   - Return score (+1, -1, 0)
2. For each possible move:
   - Simulate move
   - Call minimax recursively
   - Undo move
3. Choose:
   - **Max score** for MAX player
   - **Min score** for MIN player

---

## 💻 Features

- 🤖 AI opponent using Minimax
- 🎯 Optimal move selection
- 🔁 Recursive game state evaluation
- 🎮 Classic Tic-Tac-Toe gameplay

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AuraShivam/TicTacToe.git
