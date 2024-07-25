# Rock Paper Scissors

This is a simple Rock Paper Scissors game built using HTML, CSS, and JavaScript. The game allows a user to play against the computer by selecting one of the three choices: Rock, Paper, or Scissors.

## Demo

You can play the game [here](https://keshavmundhe477.github.io/Rock-Paper-Scissors/).

## GitHub Repository

You can view the source code and contribute to the project [here](https://github.com/<username>/<repository-name>).

## Features

- User can select Rock, Paper, or Scissors.
- The computer randomly selects Rock, Paper, or Scissors.
- Displays the result of each round (Win, Lose, or Draw).
- Keeps track of the user's and computer's scores.

## Installation

1. Clone the repository:
    ```sh
    https://github.com/keshavmundhe477/Rock-Paper-Scissors-Game.git
    ```
2. Navigate to the project directory:
    ```sh
    cd rock-paper-scissors
    ```

## Usage

1. Open `index.html` in your web browser:
    ```sh
    open index.html
    ```

2. Start playing the game by clicking on the Rock, Paper, or Scissors image to make your move.

## Code Overview

### index.html

This file contains the structure of the game. It includes a title, the choices for the user to select from, a scoreboard, and a message container to display the game result.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Rock Paper Scissors Game</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <h1>Rock Paper Scissors</h1>
    <div class="choices">
        <div class="choice" id="rock">
            <img src="./images/rock.png" />
        </div>
        <div class="choice" id="paper">
            <img src="./images/paper.png" />
        </div>
        <div class="choice" id="scissors">
            <img src="./images/scissors.png" />
        </div>
    </div>

    <div class="score-board">
        <div class="score">
            <p id="user-score">0</p>
            <p>You</p>
        </div>
        <div class="score">
            <p id="comp-score">0</p>
            <p>Comp</p>
        </div>
    </div>

    <div class="msg-container">
        <p id="msg">Play your move</p>
    </div>
    <script src="app.js"></script>
</body>
</html>
