```markdown
# Rock, Paper, Scissors Game

This is a simple Python program that simulates the classic game of Rock, Paper, Scissors. The game is played between two players, and their scores are tracked and displayed after each round.

## Author

**Madhukar Kumar**

## Game Overview

The program includes the following player types:

- **Player**: The base class for all players.
- **RandomPlayer**: A player who makes random moves.
- **HumanPlayer**: A human player who inputs their move via the console.
- **ReflectPlayer**: A player who mimics the opponent's last move.
- **CyclePlayer**: A player who cycles through the moves (rock, paper, scissors) sequentially.

## How the Game Works

- The game is played in rounds, with each player making a move (rock, paper, or scissors).
- The winner of each round is determined based on the traditional rules of Rock, Paper, Scissors:
  - Rock beats Scissors
  - Scissors beats Paper
  - Paper beats Rock
- If both players make the same move, the round is a tie.
- After three rounds, the player with the higher score wins the game.
- If the scores are tied after three rounds, the game is declared a tie.

## How to Run the Game

1. Make sure you have Python installed on your system.
2. Copy the Python code into a file named `rock_paper_scissors.py`.
3. Run the file in your terminal or command prompt:

   ```sh
   python rock_paper_scissors.py
   ```

4. When prompted, enter your name and then play the game by typing "rock", "paper", or "scissors" as your move.

5. After the first game ends, you'll have the option to play again. You can play against a different type of opponent, such as `RandomPlayer`.

## Example Output

```text
Welcome to Rock, Paper, Scissors. What's your name: John
Player's name is Cycle Player
Player's name is John
Game start!
Round 1:
Cycle Player's move: rock John's move: rock
The round was a tie
Cycle Player score = 0
John score = 0
Round 2:
Cycle Player's move: paper John's move: scissors
John won
Cycle Player score = 0
John score = 1
Round 3:
Cycle Player's move: scissors John's move: paper
Cycle Player won
Cycle Player score = 1
John score = 1
Cycle Player final score = 1
John final score = 1
The Game was a tie !!
Game over!
Do you want to play again? Type Yes or No: yes
```

## Future Enhancements

- Add more complex strategies for the computer players.
- Implement a graphical user interface (GUI) for a more interactive experience.
- Allow for more than three rounds and customizable game settings.

## License

This project is open-source and available under the MIT License.
```

This `README.md` file provides a comprehensive guide to your game, including how to run it, what to expect during gameplay, and possible future improvements.
