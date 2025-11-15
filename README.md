# Rock Paper Scissors Game

A classic implementation of the Rock Paper Scissors game developed using HTML, CSS, and vanilla JavaScript. Challenge the computer to see who can win\!

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [How to Play](#how-to-play)
- [File Structure](#file-structure)

## Features

  * **Interactive Choices:** Users can select Rock, Paper, or Scissors by clicking on the corresponding image.
  * **Computer AI:** The computer's choice is generated randomly from the three options.
  * **Score Tracking:** Separate scores are maintained and displayed for the user and the computer.
  * **Dynamic Messages:** A message box indicates the result of each round (Win, Lose, or Draw) and shows which choice beat the other.
  * **Responsive Styling:** Basic modern styling with a hover effect on choices.

## Technologies Used

  * **HTML5:** For the page structure.
  * **CSS3:** For styling and layout.
  * **JavaScript (Vanilla):** For all game logic and DOM manipulation.

## Installation and Setup

This game is a simple static website and requires no complex setup.

1.  **Clone or Download:** Get the project files onto your local machine.
2.  **Run:** Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Safari).

The game will load instantly, and you can start playing immediately.

## How to Play

1.  The game starts with the message "Play your move" and scores set to 0.
2.  Click on one of the three options: Rock, Paper, or Scissors.
3.  The computer will make its choice automatically.
4.  The winner is determined using the classic rules:
      * Rock beats Scissors.
      * Paper beats Rock.
      * Scissors beats Paper.
5.  If both the user and computer choose the same option, it's a draw.
6.  The score will be updated, and a new message will be displayed indicating the result of the round.

## File Structure

```
.
├── index.html            # Main game structure (HTML)
├── app.js                # Core game logic (JavaScript)
├── style.css             # Styling for the game (CSS)
└── images/               # Directory for game images
    ├── rock.png          # Image for Rock
    ├── paper.png         # Image for Paper
    └── scissor.png       # Image for Scissors
```