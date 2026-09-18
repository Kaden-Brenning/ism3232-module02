# ISM3232 - Module 2:zsh Navigation and File Operations

## Commands Practiced 

| Command  | What it does                         |
|----------|--------------------------------------|
|pwd       | Prints the current working directory |
|ls        | List folders / files                 |
|ls -la    | List all files including hidden      |
|cd ~      | Current directory to home            |
|cat       | Displays text content of file        |
|mv        | Move a file or Rename                |
|rm        | Remove a file / Folder               |
|mkdir     | Create a new folder                  |
|head -5   | Print first 5 lines from file        |
|tail -5   | Print last 5 lines from file         |
|grep      | Find text within a file              |
|tree      | Display the directory as a tree      |

## AI Use Statement
I did not use AI for this lab.


## Week 3: Virtual Environments and .zshrc
venv - Virtual environment, creates an isolated Python for projects
source .venv/bin/activate - activates the venv
which python3 - shows active python
pip freeze > requirements.txt - prints the current packages and version numbers to file
alias ll='ls -la' - allows creating a shortcut for commands
echo '.venv/' > .gitignore - overwrites the gitignore file with '.venv/'
echo '__pycache__' >> .gitignore - Adds to the bottom of .gitignore '__pycache__'