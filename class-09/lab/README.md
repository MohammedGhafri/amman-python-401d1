# Lab: Game of Greed 4

## Overview

Today you'll continue work on command line version of the dice game `greed` by adding an AI bot to play the game.

## Feature Tasks and Requirements

- Create an AI Bot to play Game of Greed
  - The only method available for use from Game class is `play`.
  - All static methods of `GameLogic` class are available.
  - All other interactions with game can take place **ONLY** via the I/O features of the game.
    - In other words, via injectable `print` and `input` functionality.
    - It is FORBIDDEN to inject a custom `roller` function into Game class.
- Your Bot class should be added to `player_bot.py` file with name of your choosing.
- User should be able to see your bot play by executing `player_bot.py` from terminal.
- Application should implement features from previous classes

The goal, but not requirement, is to beat **Nervous Nellie**. A Bot that banks on the first roll every time.

## Implementation Notes

- Review [rules of game](https://en.wikipedia.org/wiki/Dice_10000){:target="_blank"}
- Play game [online](http://www.playonlinedicegames.com/farkle){:target="_blank"}

### User Acceptance Tests

- No additional unit tests are required. But your bot must be playable by running `player_bot.py` from command line.

## Configuration

Continue working with team in `game-of-greed` repository

Refer to [Lab Submission Instructions](../../../reference/submission-instructions/labs/){:target="_blank"} for detailed instructions.
