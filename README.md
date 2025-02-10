# Snake-Game-Project
Snake Game

# Direct link of readme file
https://docs.google.com/document/d/1QNKhpCjg_V1Adlr1fD2tk-JCZBDHt-D-QIDmAcduqoo/edit?tab=t.0


# Description
The Snake Game is a classic console-based game implemented in C++. The player controls a snake that moves around the screen, consuming food to grow while avoiding collisions with the walls and itself. The game provides a simple yet engaging experience that tests the player's reflexes and strategic planning.

# Table of Contents
-Installation
-Usage
-Features
-Contributing
-License
-Badges

# Installation Guide
If you want to run this Snake game on your computer, here’s a simple step-by-step guide.


# 1. Install a C++ Compiler
This game is written in C++, so you’ll need to have a C++ compiler installed to run it. If you don’t already have one, here’s how you can install it:
Windows: You can install MinGW or use Visual Studio, which comes with its own compiler.
If you’re using MinGW, make sure you add it to your system's PATH so you can use the g++ command from anywhere in the terminal.
Mac: Install Xcode via the App Store, which includes clang (the Mac compiler for C++).
Linux: Install the build-essential package using this command:


# 2. Open the Project in Your IDE
Once you have the files and compiler, you can open the project in your favorite C++ IDE (like Visual Studio, Code::Blocks, or CLion). If you don’t have an IDE, you can also use any text editor (like Notepad++, Sublime Text, or VS Code) and compile the code manually.


# 3. Compile the Code
To compile the project, you’ll need to run a command in your terminal or command prompt. Here’s an example of how to compile it if you’re using g++ (MinGW or Linux/Mac terminal):

This will create an executable file called snake_game that you can run.


# 4. Run the Game
Once the game is compiled, you can run it with this command:
On Windows:
  Simply run the executable:
    bash
    CopyEdit

On Linux/Mac:
Run the game using:


# 5. Play the Game
After running the game, you should see the Snake game board in your terminal. Use the WASD keys to move the snake around the board.
          W for Up
          A for Left
          S for Down
          D for Right
The goal is to eat the food (the little "o" symbol) and make your snake longer without hitting the walls or yourself.










## Installation
To set up and run the Snake Game on your local machine, follow these steps:
Clone the repository using Git:
    git clone https://github.com/yourusername/snake-game.git
Navigate to the project directory:
    cd snake-game
Compile the code using g++:
    g++ -o snake_game snake_game.cpp -std=c++11
Run the executable:
    ./snake_game


## Usage
Once the game is running, you can start playing:
Control the Snake:
Use the arrow keys on your keyboard to control the movement of the snake:
      Up Arrow: Move the snake up
      Down Arrow: Move the snake down
      Left Arrow: Move the snake left
      Right Arrow: Move the snake right

Eat Food:
The snake will grow longer each time it eats food (represented by *). Your goal is to eat as much food as possible without colliding with the walls or your own body.
+---------------------+
|       Snake Game     |
+---------------------+
|                     |
|   *    SSSSSSSS      |
|       S              |
|       S              |
|                     |
+---------------------+

## Game Over:
The game ends when the snake collides with a wall or its own body. When this happens, your final score will be displayed.
+---------------------+
|       Snake Game     |
+---------------------+
|                     |
|   SSSSSSSS           |
|    S       X         |
|    S       S         |
|    S                 |
|   Game Over          |
|   Score: 15          |
+---------------------+

# Restart the Game:
After the game ends, press Enter to start a new game.
# Quit the Game:
You can press Q at any time to quit the game


## Objective
The goal is to navigate the snake to consume food (o) to grow in length.
Avoid collisions with the game boundaries and the snake's own body.
The game ends when the snake collides with itself or the walls.
    ## Features
    Real-time user input handling
    Randomly generated food placement
    Increasing difficulty as the snake grows
    Simple and intuitive controls
    Score tracking system

# Contributing
We welcome contributions from the community! To contribute to the project, follow these steps:
Fork the repository.
Create a new branch:
    git checkout -b feature-name
Make your changes and test them thoroughly.
Commit and push your changes:
    git push origin feature-name
Create a pull request and describe the changes you made.


Fork the Repository: Start by forking the repository to your own GitHub account.
Clone the Repository: Clone the forked repository to your local machine:
bash
Copy
git clone https://github.com/your-username/snake-game.git
Create a New Branch: Create a new branch for your feature or bug fix:
bash
Copy
git checkout -b feature/your-feature-name
Make Your Changes: Implement your changes or improvements. Ensure your code follows the existing style and structure.
Test Your Changes: Run the game locally to ensure your changes work as expected and do not introduce new bugs.
Commit Your Changes: Commit your changes with a clear and descriptive commit message:
bash
Copy
git commit -m "Add: New feature to increase game speed"
Push Your Changes: Push your changes to your forked repository:
bash
Copy
git push origin feature/your-feature-name
Create a Pull Request: Open a pull request from your branch to the main repository. Provide a detailed description of your changes and why they are beneficial.

License
This project is licensed under the MIT License, allowing open-source usage and modifications.
Badges
