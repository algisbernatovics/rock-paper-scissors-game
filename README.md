# Rock Paper Scissors Game

An object-oriented PHP implementation of an extended Rock Paper Scissors game model.

## Learning Goal

Practice modeling game choices and players with classes instead of putting all logic into one procedural script.

## Features

- Defines game elements and player behavior as classes.
- Separates model objects from the public entry point.
- Keeps the game logic readable for a small OOP exercise.

## Complexity

- Time: `O(1)` per round.
- Space: `O(1)` for the current game state.

## Tech Stack

- PHP
- Object-oriented programming

## Run

```bash
php public/RockPaperScissorsGame.php
```

## Project Structure

- `app/Models/GameElement.php` - game option representation
- `app/Models/Player.php` - player behavior
- `public/RockPaperScissorsGame.php` - entry point

## License

MIT License. See [LICENSE](./LICENSE).
