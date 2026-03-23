# Mini-Max Cube Muncher

A strategic "Batman vs Spider-Man" themed game where players take turns removing cubes from a table. The player who removes the last cube wins the game!

## Overview

In this arcade-style strategy game, you play as **Spider-Man** against **Batman (AI)**. Batman utilizes the power of the **Minimax Algorithm** to calculate his moves, making him a formidable opponent.

## Rules of the Game

### Setup
Before the game starts, two key parameters are set:
- **M (Cubes on Table)**: The total number of cubes initially available (must be 4 or more).
- **K (Special Pick)**: A special number of cubes that can be removed in a single turn (must be between 2 and M).

### Gameplay
- **Turn Order**: Batman (AI) always goes first.
- **Possible Moves**: On each turn, a player can choose to remove either **1**, **2**, or **K** cubes from the table.
- **Objective**: The player who successfully removes the **last cube** from the table is declared the winner!

## Technology

The game's AI is powered by a **Minimax Algorithm** with memoization, ensuring that Batman always plays optimally for the given game state.
