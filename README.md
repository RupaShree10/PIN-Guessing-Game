# PIN Guessing Game 🔐

A Python-based PIN Guessing Game where the computer generates a random PIN and the player must guess it. The game provides feedback for each digit, helping the player identify which positions are correct.

## Features

* Three difficulty levels:

  * Easy (4-digit PIN)
  * Medium (6-digit PIN)
  * Hard (8-digit PIN)
* Input validation to ensure correct PIN length.
* Feedback for every digit guessed.
* Tracks the number of attempts taken to win.
* Leaderboard system using a CSV file.
* Displays Top 5 Fastest Wins.
* Play Again option.

## How It Works

1. Enter your name.
2. Choose a difficulty level.
3. The computer generates a random PIN.
4. Enter your guesses.
5. After each guess, the game tells you which digit positions are correct.
6. Keep guessing until you crack the PIN.
7. Your score is saved to the leaderboard.

## Technologies Used

* Python
* Functions
* Loops
* Exception Handling
* File Handling (CSV)
* Random Module

## Sample Gameplay

Enter your name: Rupa

Choose difficulty (Easy: 4 digits, Medium: 6 digits, Hard: 8 digits): easy

Guess the PIN (4 digits): 1234

Digit 1 is correct

Digit 2 is incorrect

Digit 3 is incorrect

Digit 4 is correct

Guess the PIN (4 digits): 1538

Congratulations Rupa, you guessed it in 2 attempts!!

## Learning Outcomes

This project helped me practice:

* Functions
* Loops
* Conditional Statements
* Exception Handling
* String Manipulation
* File Handling
* Python Modules
* Basic Game Development

## Future Improvements

* Hint system
* Difficulty-based scoring
* Timer mode
* GUI version using Tkinter or PyQt
* Online leaderboard

## Author

Rupa Shree

A beginner Python project built as part of my programming learning journey.
