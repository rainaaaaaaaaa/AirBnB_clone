# Command Interpreter Project

## Description

This project involves building a simple command-line interpreter in Python. The interpreter provides a shell interface that accepts various commands and executes them. The project follows a modular structure to ensure maintainability and scalability.

## Command Interpreter

The command interpreter allows users to interact with the system via commands. It supports basic functionalities like help, quit, and EOF.

### How to Start It

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your_username/your_repository.git
    cd your_repository
    ```

2. **Make the `console.py` executable:**
    ```bash
    chmod +x console.py
    ```

3. **Run the command interpreter:**
    ```bash
    ./console.py
    ```

### How to Use It

Once the interpreter is running, you will see a prompt `(hbnb)`. You can type commands after the prompt.

#### Commands:

- **help:** Displays a list of available commands or detailed help for a specific command.
    ```bash
    (hbnb) help
    (hbnb) help <command>
    ```

- **quit:** Exits the command interpreter.
    ```bash
    (hbnb) quit
    ```

- **EOF:** Exits the command interpreter using the EOF signal (Ctrl+D).
    ```bash
    (hbnb) EOF
    ```

### Examples

#### Interactive Mode

```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) quit
$
