# Blackjack

![License](https://img.shields.io/badge/license-MIT-green) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow) ![Status](https://img.shields.io/badge/status-Complete-brightgreen)

[![Play Demo](https://img.shields.io/badge/Play-Demo-success)](https://to8-bj.netlify.app/)

A custom implementation of the classic Blackjack card game.

<img width="959" height="506" alt="image" src="https://github.com/user-attachments/assets/813ae9b7-6ae3-49a6-8d65-79ee72ed6b94" />

## Features

* Single-player Blackjack against the dealer
* Standard Blackjack rules
* Dynamic Ace value handling (1 or 11)
* Hit, Stand, and Split mechanics
* Automatic dealer play
* Clean and modern interface
* Randomized card shuffling

## Future Improvements(maybe)

* Double Down
* Insurance
* Betting system
* Game statistics
* Sound effects
* Multiplayer support

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## Game Rules

1. The goal is to get as close to **21** as possible without going over.
2. Number cards are worth their face value.
3. Face cards (Jack, Queen, King) are worth **10** points.
4. Aces are worth **11** or **1**, whichever benefits the hand most.
5. Players start with two cards and may:

   * **Hit**: Draw another card.
   * **Stand**: End their turn.
   * **Split**: If the first two cards have the same value, the player may divide them into two separate hands. Each hand receives an additional card and is played independently. Both hands are then compared against the dealer's hand separately.
6. The dealer draws until reaching at least **17**.
7. If a hand exceeds **21**, it busts and loses automatically.

## Installation

Clone the repository:

```bash
git clone https://github.com/to8zljghvru/blackjack.git
cd blackjack
```

## Running the Game

```bash
npm start
```

Or:

```bash
python main.py
```

## Project Structure

```text
blackjack/
├── cards/
│   └── pictures
├──blackjack.css
├── blackjack.js
├── index.html
└── README.md
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
