<div align="center">

# Tic-Tac-Toe

**A classic two-player game built with HTML, CSS, and JavaScript.**

[**Play the Live Demo**](https://parvathyamvk.github.io/prodigy-wd-task-03-tic-tac-toe/)

</div>

---

## Overview

Tic-Tac-Toe is a browser-based game for two players. Players take turns marking spaces on a 3 × 3 grid with **X** and **O**. The game checks for a winning combination after each move and identifies a draw when the board is full.

## Features

- **Two-player mode** — take turns playing as X and O.
- **Win detection** — checks all eight possible winning combinations: rows, columns, and diagonals.
- **Draw detection** — recognises when all nine cells are filled without a winner.
- **Reset control** — clear the board and start a new round at any time.
- **Immediate result messages** — displays an alert when a player wins or the game ends in a draw.
- **Automatic new round** — resets the board after a win or draw.

## Built With

| Technology | Purpose |
|---|---|
| HTML5 | Game structure and 3 × 3 board |
| CSS3 | Layout, board styling, and button hover effect |
| JavaScript | Player turns, game logic, win/draw checks, and reset behaviour |

## Getting Started

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/parvathyamvk/prodigy-wd-task-03-tic-tac-toe.git
   ```

2. Move into the project directory:

   ```bash
   cd prodigy-wd-task-03-tic-tac-toe
   ```

3. Open `index.html` in your web browser.

No package installation or build process is required.

## How to Play

1. Player **X** takes the first turn.
2. Select an empty square to place your mark.
3. Player **O** takes the next turn.
4. Continue taking turns until a player completes a row, column, or diagonal.
5. If all nine squares are filled and nobody has won, the game is a draw.
6. Select **Reset** to start a fresh game. The board also resets automatically after a win or draw.

## Project Structure

```text
prodigy-wd-task-03-tic-tac-toe/
├── index.html    # Game page and board markup
├── styles.css    # Page, board, cell, and button styling
├── script.js     # Game interactions and win/draw logic
└── README.md     # Project documentation
```

## Implementation Notes

- The game starts with **X**.
- A move is accepted only when the selected cell is empty.
- The win checker evaluates the eight standard Tic-Tac-Toe winning patterns.
- After a win or draw, the result is shown using a browser alert and the board is cleared.

## Live Demo

Try the deployed game:

[https://parvathyamvk.github.io/prodigy-wd-task-03-tic-tac-toe/](https://parvathyamvk.github.io/prodigy-wd-task-03-tic-tac-toe/)

## Author

**Parvathy A**

[GitHub Profile](https://github.com/parvathyamvk)

---

<div align="center">

Made as part of the **PRODIGY Web Development Internship** task series.

</div>
