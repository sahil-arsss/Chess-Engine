# Chess Engine (Minimax with Alpha-Beta Pruning)

This is a web-based Chess AI application built using `HTML5`, `CSS3`, and `JavaScript`. The chessboard UI is handled by `chessboard.js`, while game logic (move generation, validation, etc.) is managed by `chess.js`.

The AI makes decisions using the **Minimax algorithm** with **alpha-beta pruning** and a custom evaluation function based on material and positional scoring.

## 🌟 Features

- Interactive chessboard UI
- Valid move generation
- Play against the AI (Black side)
- AI logic based on Minimax algorithm with alpha-beta pruning
- Evaluation function with:
  - Piece weights (e.g. Queen = 929, Pawn = 100)
  - Piece-square tables for positional advantage

## 🧠 How It Works

1. **Evaluation Function**  
   Assigns scores to board states based on material + piece positions.

2. **Minimax Algorithm**  
   Searches game tree to simulate opponent's optimal moves up to a depth limit.

3. **Alpha-Beta Pruning**  
   Optimizes Minimax by pruning unnecessary branches to reduce computation.

## 🧱 Tech Stack

- `HTML5`
- `CSS3`
- `JavaScript`
- [`chessboard.js`](https://chessboardjs.com/)
- [`chess.js`](https://github.com/jhlywa/chess.js)

![image](https://github.com/user-attachments/assets/a7f8456c-3735-4610-a789-1d9278bb8c36)


## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/sahil-arsss/Chess-Engine.git
cd Chess-Engine
