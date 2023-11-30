# Number Guessing Game

This is a simple console-based Number Guessing Game implemented in C#.

## Description

The Number Guessing Game is a classic game where the player tries to guess a randomly generated number within a specified range. In this case, the range is between 0 and 100.

## How to Play

1. Run the program.
2. The program will generate a random number between 0 and 100.
3. You'll be prompted to guess the number.
4. After each guess, the program will provide feedback, indicating whether your guess is too high or too low.
5. Keep guessing until you correctly guess the number.

## Code Overview

The game is implemented in C# and consists of a single console application. Here's a brief overview of the key components:

- **Random Number Generation:** The program uses the `Random` class to generate a random number between 0 and 100.

- **User Input:** The player is prompted to input their guess using the `Console.ReadLine()` method.

- **Feedback:** The program provides feedback based on the user's guess, informing them whether the guess is too high, too low, or correct.

- **Looping:** The game is played within a `do-while` loop, ensuring that the player continues to guess until they correctly identify the random number.

## Getting Started

To run the game, follow these steps:

1. Ensure you have a C# compiler installed.
2. Copy the provided C# code into a new or existing C# console application.
3. Compile and run the program.

## Example

```csharp
Guess a number between 0 and 100: 50
Too high! Guess lower...
Guess a number between 0 and 100: 25
Too low! Guess higher...
Guess a number between 0 and 100: 37
You are correct!
```

##### Credits to Fransesco Magliocco for his tutorial
