# AI Number Guessing Game

A simple Python 3 game where the AI attempts to guess a number between 1 and 100 that the player is thinking of. The AI learns and adjusts its guesses based on feedback until it correctly guesses the number. This project is beginner-friendly and demonstrates basic Python concepts, such as loops, conditional statements, and user input.

## Features
- AI makes educated guesses to find the correct number.
- The game adjusts the AI's "learning rate" for better guess accuracy over time.
- Provides simple user feedback for an interactive experience.

## How It Works
1. The player thinks of a number between 1 and 100 (inclusive).
2. The AI makes a guess based on the midpoint of the remaining range.
3. The player provides feedback: 
   - **"H"** if the guess is too high,
   - **"L"** if the guess is too low,
   - **"C"** if the guess is correct.
4. The AI narrows down the range and updates its guesses based on the feedback until it guesses correctly.

## Prerequisites
- Python 3

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ai-number-guessing-game.git


