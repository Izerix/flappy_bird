Flappy Bird in Godot

This project is a simple Flappy Bird clone developed using the Godot game engine. The goal of this project is to demonstrate basic 2D game development concepts, including physics, collision detection, and scene management in Godot.

Features

Procedurally generated pipes

Simple physics-based movement

Score tracking

Restart functionality

Requirements

Godot Engine (version 3.x or 4.x)

Installation

Clone the repository:

git clone https://github.com/your-repo/flappy-bird-godot.git

Open the project in Godot.

Run the game by pressing the "Play" button.

Controls

Press Spacebar or Left Mouse Button to make the bird flap.

Avoid hitting the pipes or the ground.

File Structure

flappy-bird-godot/
│-- assets/ # Sprites and sound files
│-- scenes/ # Game scenes (main, player, pipes, etc.)
│-- scripts/ # GDScript files controlling the game logic
│-- project.godot # Godot project file

How It Works

The bird has a gravity effect applied and flaps upward when the player presses the input key.

Pipes spawn at random heights and move from right to left.

If the bird collides with a pipe or the ground, the game restarts.

Score increases when the bird successfully passes through a pair of pipes.

License

This project is released under the MIT License. Feel free to modify and distribute it.

Credits

Developed using Godot Engine

Inspired by the original Flappy Bird game

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
