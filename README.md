# Command-Line Casino Game

Welcome to the Command-Line Casino Game, where you can test your luck and win big! This simple C++ game allows you to place bets and guess the outcome of a dice roll. Will you be able to multiply your winnings, or will luck elude you? Give it a try and see if you can amass a fortune!

## How to Play

1. **Enter Your Name:** Start by entering your name to personalize the gaming experience.

2. **Deposit Amount:** Enter the initial amount you want to start the game with. This will be your virtual balance for betting.

3. **Rules:** Before you begin, the rules of the game will be displayed. Make sure to read them carefully.

4. **Place Your Bets:** You can bet a certain amount from your balance. Make sure you don't bet more than what you have.

5. **Guess the Number:** Choose a number between 1 and 10 that you think the dice will roll.

6. **Roll the Dice:** The dice will be rolled, and the outcome will be revealed.

7. **Win or Lose:** If your guess matches the rolled number, you win 10 times the amount you bet. Otherwise, you lose the bet amount.

8. **Continue or Quit:** After each round, you can choose to play again or quit the game based on your remaining balance and inclination to keep playing.

Remember, the game continues as long as you have funds to bet with. If your balance reaches zero, it's game over.

## Compilation and Execution

To play the game, follow these steps:

1. Open a terminal window.

2. Navigate to the directory where the game's source code is located.

3. Compile the code using a C++ compiler:
```
g++ -o casino_game casino_game.cpp
```
4. Run the compiled executable:
```
./casino_game
```
## Requirements

- C++ Compiler (like g++)
- Standard Library (iostream, string)
- Operating System: Windows (for `system("cls")`) or adjust clearing screen logic for other operating systems


