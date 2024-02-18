# Dice Game

This JavaScript code represents a simple dice game where two players take turns rolling a dice. The objective of the game is to be the first player to reach a score of 100.

## Features

- Roll the dice: Players can roll a dice and accumulate points based on the dice roll, unless they roll a 1.
- Hold score: Players can choose to "hold" their current score, adding it to their total score and passing the turn to the next player.
- Winning condition: The game ends when one player reaches a score of 100 or more.
- New game: Players can start a new game at any time, resetting the scores and starting conditions.

## How to Use

1. Open the `index.html` file in your browser.
2. Click the "New Game" button to start a new game.
3. Click the "Roll Dice" button to roll the dice. Each roll adds to your current score unless you roll a 1.
4. Click the "Hold" button to add your current score to your total score and pass the turn to the next player.
5. The first player to reach a score of 100 or more wins the game.

## Code Explanation

- The `init` function initializes the game state, setting scores, current scores, active player, and playing status.
- The `switchPlayer` function switches the active player and resets the current score to 0.
- Event listeners are attached to the "Roll Dice", "Hold", and "New Game" buttons to handle game actions.
