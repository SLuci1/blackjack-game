# Blackjack Game — JavaScript

Interactive Blackjack game built in vanilla JavaScript as part of a Scrimba learning project.

The game simulates a simplified Blackjack round where the player draws cards and tries to reach 21 without exceeding it.

## Overview

This project focuses on learning core JavaScript fundamentals through a small browser game:

* game state management
* DOM manipulation
* conditional logic
* random number generation
* user interaction via buttons

## Features

* Start a new Blackjack round
* Random card generation (Ace = 11, Face cards = 10)
* Dynamic card display
* Running total calculation
* Win / lose game logic
* Player profile with chips display
* Interactive UI updated in real time

## Game Rules (Simplified)

* The player starts with two random cards.
* Cards between 2–10 keep their value.
* Jack, Queen and King count as 10.
* Ace counts as 11.
* Reach 21 → Blackjack.
* Go above 21 → player loses.
* The player can draw additional cards while still alive.

## Technologies

* HTML5
* CSS3
* JavaScript (Vanilla ES6)

## Project Structure

blackjack-game/
├── index.html
├── index.css
├── index.js
└── img/
    └── table.jpg

## What I Practiced

* Using objects and arrays in JavaScript
* Updating the DOM dynamically
* Managing application state (`isAlive`, `hasBlackJack`)
* Writing reusable functions
* Basic game logic implementation

## How to Run

1. Clone the repository
2. Open `index.html` in your browser

## Live Demo

![Preview screenshot](/img/preview.png)

## Author

Lucien — Web Developer