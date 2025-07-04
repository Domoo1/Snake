# Snake

A classic Snake game implemented in C# using WPF and .NET 8.

## Features

- Smooth keyboard controls
- Dynamic grid-based gameplay
- Growing snake and food mechanics
- Simple, clean UI

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- Visual Studio 2022 or later (recommended)

### Running the Game

1. Clone this repository: git clone https://github.com/Domoo1/Snake
2. Open the solution in Visual Studio.
3. Set the project as the startup project.
4. Press `F5` to build and run.

### Controls

- **W, A, S, D**: Move the snake (Up, Left, Down, Right)

## Project Structure

- `GameState.cs` – Core game logic and state management
- `Direction.cs` – Direction enumeration for snake movement
- `GridValue.cs` – Grid cell value definitions
- `Images.cs` – Image resources for rendering
- `MainWindow.xaml` / `MainWindow.xaml.cs` – UI and event handling
- `Position.cs` – Represents a position on the game grid, including translation and equality logic
## Screenshots

![Game Start](Screenshots/start.png)
*Game start screen*

![Gameplay](Screenshots/game.png)
*Gameplay in progress*

![Game Over](Screenshots/end.png)
*Game over screen*


Enjoy playing Snake!