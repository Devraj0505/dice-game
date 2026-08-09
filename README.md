# Dice Game

A simple browser-based two-player dice game built with HTML, CSS, and JavaScript.

## How to play

- Click **Roll dice** to roll a six-sided die.
- If the roll is not `1`, the value is added to the current player's round score.
- If the roll is `1`, the current player's round score is lost and the turn switches to the other player.
- Click **Hold** to add the current round score to the active player's total score and pass the turn.
- The first player to reach the winning score wins the game.

## Files

- `index.html` — game structure and buttons.
- `style.css` — page layout, player panels, and visual styling.
- `script.js` — gameplay logic, dice rolls, turn switching, and win conditions.
- `dice-1.png` to `dice-6.png` — dice face images used for the roll animation.

## Run locally

1. Open `index.html` in a web browser.
2. Play the game using the buttons on the page.

## Notes

- The current win condition is set to a score of `20`.
- Click **New game** to reset scores and start over.
