# UberGame

UberGame is a simple DnD-style combat game written in C# for .NET Core 2.1. Players create a character, choose a class, and battle against a villain in a turn-based fight.

## Features

- Character creation with name and class selection (Warrior, Rogue, or Peasant)
- Randomized weapon stats and dice rolls for attacks
- Turn-based combat loop between player and villain
- Simple console-based UI for input and output
- Sound effects using `Console.Beep` for music and dramatic moments

## Project Structure

- `Program.cs` - Entry point, starts the game
- `Game.cs` - Main game logic and combat loop
- `Character.cs` - Player and villain character logic and stats
- `Weapon.cs` - Weapon logic and random attack value
- `Die.cs` - Dice rolling utilities (1d6, 2d6, 1d20)
- `MusicBox.cs` - Plays intro, battle, and dramatic sounds
- `UI.cs` - Handles user input for character creation

## How to Run

1. Make sure you have [.NET Core 2.1 SDK](https://dotnet.microsoft.com/download/dotnet/2.1) installed.
2. Build and run the project:

   ```sh
   dotnet run
   ```

3. Follow the prompts in the console to play.

## Example Gameplay

- Enter your character's name and class.
- Fight the villain in a turn-based loop.
- The game announces the winner at the end.

---

Made as a school assigment in XAMK
