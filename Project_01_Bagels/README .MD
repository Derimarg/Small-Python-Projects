# Project 01: Bagels

**Bagels**, by [AL Sweigart](mail:al@inventwithpython.com)

A deductive logic game where you must guess a number based on clues.

## Overview

In the game, the computer thinks of a secret 3-digit number with no repeated digits. The player must guess the number within a limited number of attems (10 by default). After each guess, the computer provides clues to help the player deduce the secret number:

- **Pico**: One digit is correct but in the wrong position.
- **Fermi**: One digit is correct and in the right position.
- **Bagels**: No digit is correct.

For example, if the secret number is `248` and the player guesses `843`, the clues would be "Fermi Pico" (because '4' is correct and in the right position, and '8' is correct but in the wrong position).

## How to play

1. Run the script using Python:

  ```bash
  python bagels.py
  ```

or if you have python version 3 installed, use:

  ```bash
  python3 bagels.py
  ```

2. Follow the propmsps to guest the secret bumber base on the clues provided.
3. Keep guessing until you either guess the number correctly or run out of guesses.
4. You can choose to play again after each round.

## Customization

You can modify the game by changing the following parameters in the code:

- **NUM_DIGITS**: The length of the secret number (default is 3).
- **MAX_GUESSES**: The maximun number of guesses allowed (default is 10).

Try experimenting with different values to increase the difficulty or to suit your preferences!

## Additional Information

This code is based on the project from the book "The Big Book of Small Python Projects." A version of this game is also featured in the book "Invent Your Own Computer Games with Python" by Al Sweigart.

- Learn more: [No Starch Press - The Big Book of Small Python Porjects](https://nostarch.com/big-book-small-python-projects)
- Explore more Python games: [Invent Your Own Computer Games with Python](https://nostarch.com/inventwithpython)

## Tags

short, game, puzzle

Enjoy playing **Bagels** and improving your deductive reasoning skills!