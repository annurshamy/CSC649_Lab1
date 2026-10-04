# CSC649 

## Program Description

This program accepts a sentence from the user and displays the number of words and characters in the sentence. It also displays a message when the user does not enter a sentence.

## How to Run

1. Open the project in PyCharm.
2. Make sure the project uses the Python 3.12 virtual environment.
3. Open `main.py`.
4. Run the program.
5. Enter a sentence when prompted.

## Test Results

| Test | Input | Result |
|---|---|---|
| Normal sentence | `I love learning Python` | Word count: 4, Character count: 22 |
| Empty input | Empty input | Displays "You did not enter a sentence." |
| Extra spaces | `I    love   Python` | Word count: 3, Character count: 18 |

All three tests produced the expected results.

## Git Commits

1. `Initial word count program`
2. `Add character count and empty input handling`

## Limitation

The program only processes one sentence at a time and does not save the input or results after the program ends.