# Rock, Paper, Scissors Game

This project implements a simple console-based Rock, Paper, Scissors game in C#. The game allows a player to compete against an AI opponent by selecting one of three choices: rock, paper, or scissors. The game determines the winner based on the choices made by the player and the AI opponent.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Acknowledgments](#Acknowledgments)

## Installation

To play the game locally, follow these steps:
skriv en installationsguide


## Usage

To use this code, follow these steps:

1. **Compile and Run**: Compile the code using a C# compiler and run the executable. This can typically be done with the `dotnet run` command if you're using .NET Core or by compiling the code into an executable and running it directly.

2. **Game Loop**: The program will enter a game loop where it prompts the player to choose between "rock," "paper," or "scissors" by entering one of these options.

3. **Game Play**: After the player makes their choice, the program will randomly select a choice for the opponent (AI). Both choices will be displayed.

4. **Determining the Winner**: The program will determine the winner based on the classic rules of rock-paper-scissors and display the result.

5. **Repeat or Quit**: After each round, the program will ask if you want to play another round. Enter "ja" to continue or any other input to quit.

Here's an example of how to use the code:

```csharp
// Compile and run the code

// Game Loop begins
// Player is prompted to choose
// Example interaction:
// > v�lj sten sax eller p�se
// > sten
// Output:
// spelarens val: sten
// motst�ndarens val: sax
// Vilken tur du har, du vann!
// Vill du spela en runda till? ja/nej
// Example interaction:
// > ja
// Game Loop continues
// ...



## Features
- Player vs. AI gameplay.
- Simple and intuitive user interface.
- Determination of game winner based on choices made by the player and AI opponent.

## License
Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## Acknowledgments
- Inspired by the classic game of rock, paper, scissors.
