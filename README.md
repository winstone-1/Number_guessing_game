# Guess the Number

A number guessing game with difficulty levels, hints, and a leaderboard. Built with Python and Jupyter Notebook.

## Run it

Open `main.ipynb` in VS Code and run the cells top to bottom.

## How it Works

Run Cell 1 to pick your difficulty, Cell 2 plays the game, Cell 3 saves your score and shows the leaderboard. Variables carry across cells so run them in order.

## Difficulty Levels

| Level | Tries |
|-------|-------|
| Easy | 10 |
| Medium | 7 |
| Hard | 5 |

## Features

- Random number generated between 1 and 100 each game
- Too High / Too Low feedback after every guess
- Hint unlocks after 3 wrong guesses (even or odd)
- Input validation — handles letters, out of range numbers, empty input
- Scores saved to `scores.txt` with your name, attempts, and difficulty
- Leaderboard shows top 10 players sorted by fewest attempts

## Scoring

Fewer attempts = better score. The leaderboard ranks players by how few guesses it took to get the right answer.

## Requirements

- Python 3.x
- Jupyter Notebook or VS Code with Jupyter extension

## License

MIT