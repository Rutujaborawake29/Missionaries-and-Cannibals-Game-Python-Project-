# Missionaries and Cannibals River Crossing Game
#link for game  -https://www.novelgames.com/en/missionaries/

## Overview
This project is a Python implementation of the classic **Missionaries and Cannibals River Crossing Puzzle**. The objective is to transfer all the missionaries and cannibals from one side of the river to the other without violating the game’s constraints.

## Game Objective
Safely transport **three missionaries** and **three cannibals** across the river using a boat, ensuring that missionaries are never outnumbered by cannibals on either side.

### Win Condition:
- All missionaries and cannibals are successfully transferred to the left side of the river.

### Lose Condition:
- If at any point, the number of cannibals exceeds the number of missionaries on either side of the river.

## Game Rules
1. The boat can carry **one or two people** at a time.
2. The boat cannot move if it is empty.
3. The number of missionaries or cannibals on the boat cannot exceed their availability on either side of the river.
4. The game ends if the cannibals ever outnumber the missionaries on any side.
5. The game is won when all characters successfully cross the river.

## Notebook Structure
The project is divided into the following sections:

- **Lesson 1:** Setting up the game environment.
- **Lesson 2:** Defining valid and invalid moves based on game rules.
- **Lesson 3:** Implementing the complete game logic.
- **Lesson 4:** Enhancing the game interface with visuals/emoticons for better user experience.

## Sample Code Snippet
Here’s an example of how the game initializes:

```python
boat_side = 'Right'
missionaries_on_right = 3
cannibals_on_right = 3
missionaries_on_left = 0
cannibals_on_left = 0

print("ML=", missionaries_on_left, "CL=", cannibals_on_left, "| -----B |", "MR=", missionaries_on_right, "CR=", cannibals_on_right)
```
Happy Coding! 🎮🚣‍♂️

