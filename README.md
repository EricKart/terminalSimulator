#terminalSimulator
Interactive Git Terminal Simulator
This project is a web-based, interactive terminal that simulates common Git commands. It provides a safe and hands-on environment for users to practice Git without needing to install it locally. The entire simulation runs in the browser using HTML, CSS, and vanilla JavaScript.

This tool was created as a companion to the "Mastering Version Control" article to provide a practical way for learners to apply concepts as they read them.

Features
Zero Installation: Runs entirely in the browser. No setup required.

Simulated File System: Create and manage files using familiar commands like ls, touch, echo, and cat.

Core Git Command Simulation: Practice the most essential Git commands:

git init

git add

git commit

git log

git status

git branch

git checkout

Realistic Terminal Interface: A clean, responsive terminal window with command history (using up/down arrow keys).

Branch Indicator: The command prompt always shows the current active branch.

How to Use
Clone this repository to your local machine.

Open the index.html file directly in your web browser (e.g., Chrome, Firefox, Safari).

The terminal will load, and you can start typing commands.

Supported Commands
File System
Command

Description

ls

List files in the current directory.

touch <filename>

Create a new empty file.

echo "content" > <file>

Write text content into a file.

cat <filename>

Display the content of a file.

clear

Clear all output from the terminal screen.

help

Show a list of all available commands.

Git
Command

Description

git init

Initializes a new, empty Git repository.

git add <filename>

Stages a file for the next commit.

git commit -m "msg"

Commits the staged files with a message.

git log

Shows the commit history for the current branch.

git status

Displays the status of the working directory and staging area.

git branch

Lists all local branches.

git branch <name>

Creates a new branch.

git checkout <name>

Switches to the specified branch.

Feel free to fork this project, suggest improvements, or add more features!