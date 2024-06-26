# Connect 4 Game

This is a simple implementation of the classic Connect 4 game using HTML, CSS (Tailwind CSS), and JavaScript. The game allows two players to play against each other on the same computer.

## Table of Contents

- [Overview](#overview)
- [Game Rules](#game-rules)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [How to Play](#how-to-play)
- [Features](#features)

## Overview

Connect 4 is a two-player game in which players take turns dropping colored discs from the top into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

## Game Rules

- The game is played on a grid that's 7 columns by 6 rows.
- Players take turns dropping a disc into one of the columns.
- The disc falls straight down, occupying the next available space within the column.
- The first player to get four of their discs in a row (horizontally, vertically, or diagonally) wins.
- If the board fills up before either player achieves four in a row, the game is a draw.

## Technologies Used

- HTML
- CSS (Tailwind CSS)
- JavaScript

## Setup

To run this game locally on your machine, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/supreetSekhon/Connect-4.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Connect-4
    ```
3. **Open the `index.html` file in your web browser:**
    ```bash
    open index.html
    ```

## How to Play

1. Open the game in your web browser.
2. Players take turns clicking on the columns to drop their discs.
3. The first player to get four discs in a row wins.
4. Click "Reset Game" or "Start new Game" to reset the board and play again.

## Features

- Two-player game on the same computer.
- Visual indication of the current player’s turn.
- Automatic checking for a winner after each turn.
- Displays the winning player when four in a row is achieved.
- Reset the game and start a new game functionality.
