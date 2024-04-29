# Tic Tac Toe made using Pygame.
This is a simple Tic Tac Toe game built using Python, Pygame, and Pygame GUI Basics (Pygabag). The game features a small screen where two players can play Tic Tac Toe with an additional twist - after every 3 turns, the oldest move on the board is automatically deleted.

<p align='center'>
  <img width="303" alt="image" style="horizontal-align:middle" src="https://github.com/NateshReddy/tic-tac-toe-refreshed/assets/47558025/45ce384c-d9b6-4642-9fe1-61f1d898eda4">
</p>


## Installations
Before running the game, ensure you have the following libraries installed:

* Python 3.x
* Pygame
* Pygabag

You can install Pygame and Pygabag using pip:
```bash
pip install pygame
pip install pygbag
```

## How to Play
### Local Launch:
* Run Locally with Python: Execute the command python main.py in your terminal to launch the game. This will open a small window locally, displaying the Tic Tac Toe board.

### Server Launch:
* Run with Pygabag: Alternatively, you can start a server using Pygabag by running pygbag folder-name in your terminal. This will start a server and run the game on localhost, allowing you to play the game in a web browser.

### Gameplay:
Players take turns placing their markers (X or O) on the board by moving the arrow and clicking on the desired cell. The game automatically tracks the number of turns and enforces the additional rule of removing the oldest move after every 3 turns.

### Winning the Game:
The game ends when one of the players achieves a winning combination (3 marks in a row, column, or diagonal). The winner is displayed on the screen.

## Deployment
The code is deployed using AWS S3 static web hosting, providing a simple and efficient way to share and play the game online.
