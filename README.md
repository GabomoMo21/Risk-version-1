# Crazy Risk

A strategy game project built with **C# and Godot**, created to practice object-oriented programming, modular game logic, scene organization, and collaborative software development.

The repository contains a Godot project organized into scenes and C# scripts, with gameplay behavior separated from the engine configuration and project assets.

## Highlights

- Strategy-game implementation using **C#**
- Built with the **Godot Engine**
- Object-oriented game logic
- Modular scripts and scene-based organization
- Separation between game behavior and presentation
- Git/GitHub-based development workflow

## Tech Stack

- **C#**
- **Godot Engine**
- Object-Oriented Programming
- Git / GitHub

## Repository Structure

```text
Risk-version-1/
├── Scenes/
├── Scripts/
├── CrazyRisk.csproj
├── CrazyRisk.sln
├── project.godot
├── .editorconfig
├── .gitattributes
└── .gitignore
```

## Architecture

### Scenes

Godot scenes define the main game objects and visual structure. Keeping scene definitions separate from the C# code makes it easier to organize the game and modify presentation without placing all behavior in a single file.

### Scripts

Game behavior is implemented through C# scripts. The project uses an object-oriented approach so responsibilities can be distributed across game components rather than being concentrated in one monolithic script.

## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/GabomoMo21/Risk-version-1.git
cd Risk-version-1
```

2. Open the folder from Godot.
3. Allow Godot/.NET to restore or build the C# project if requested.
4. Run the main project scene.

> A Godot installation with C#/.NET support is required.

## What I Practiced

- Building gameplay systems with C#
- Object-oriented design in a game-engine environment
- Organizing a project with reusable scenes and scripts
- Working with a multi-file codebase
- Using Git/GitHub to manage a software project

## Future Improvements

- Add a complete gameplay overview with screenshots/GIFs
- Add setup details for the exact Godot/.NET version used
- Add automated tests for game-rule logic where practical
- Improve documentation of the main classes and scene flow

## Author

**Gabriel Morales**  
Computer Engineering student  
GitHub: [@GabomoMo21](https://github.com/GabomoMo21)
