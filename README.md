# Rock-Paper-Scissors Game

A simple browser-based Rock-Paper-Scissors game built with HTML, CSS, and JavaScript. The project lets a player choose rock, paper, or scissors, compares the selection against a random computer move, and updates the score in real time.

## Overview

This project is a beginner-friendly front-end game that demonstrates the core concepts of:

- DOM manipulation
- Event handling
- Randomized computer decisions
- Score tracking
- Conditional logic for game rules

It is designed to be easy to understand and is a great example of how JavaScript can be used to create interactive web experiences without any frameworks or backend.

## Project Features

- Three clickable choices: Rock, Paper, and Scissors
- Random AI/computer move generation
- Real-time score updates for both player and computer
- Draw handling when both players pick the same option
- Visual feedback for win/loss results
- Clean, responsive UI with styled cards and scoreboard

## How the Game Works

1. The user clicks one of the three options.
2. The browser reads the selected value from the clicked element.
3. The computer generates a random choice from the same three options.
4. The game compares the two choices using standard Rock-Paper-Scissors rules.
5. The score is updated based on the result.
6. A status message shows whether the round was a win, loss, or draw.

### Winning Rules

- Rock beats Scissors
- Paper beats Rock
- Scissors beats Paper

If both selections match, the game is considered a draw.

## File Structure

- `lecture10.html` — main page structure and UI layout
- `lecture10.css` — styling for the game board, cards, score panel, and status message
- `lecture10.js` — game logic, random move generation, score updating, and click events
- `images/` — visual assets for Rock, Paper, and Scissors choices

## Logic Flow

The JavaScript follows a straightforward game cycle:

- Initialize score variables for the user and computer
- Listen for click events on each choice
- Determine the computer's random choice
- Compare user choice vs computer choice
- Update the appropriate score
- Display the result message with a matching color theme

Example decision logic:

- If both selections are the same: result is a draw
- If the user chooses Rock and the computer chooses Paper: user loses
- If the user chooses Paper and the computer chooses Scissors: user loses
- Otherwise: player wins

## Getting Started

### Prerequisites

- A modern web browser such as Chrome, Edge, Firefox, or Safari
- No installation or package manager is required

### Run the Project

1. Download or clone the project files.
2. Open `lecture10.html` in your browser.
3. Start playing the game by clicking on the Rock, Paper, or Scissors icons.

## Technologies Used

- HTML5 for page structure
- CSS3 for layout and visual styling
- JavaScript for game logic and interactions

## Learning Purpose

This project is a good beginner exercise for understanding:

- JavaScript variables and functions
- Event listeners
- Random number generation
- DOM selection and text updates
- Real-world decision-making logic in web apps

## Conclusion

This Rock-Paper-Scissors game is a simple but effective example of how front-end web technologies can be combined to build an interactive application. It is easy to follow, visually engaging, and a strong foundation for learning JavaScript-based UI logic.
