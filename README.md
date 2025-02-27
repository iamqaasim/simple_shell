# Simple Shell

This is a simple shell program written in C. It mimics the basic functionality of a Unix shell, such as executing commands, handling user input, and supporting environment variables.

## Features

- **Command Execution**: Run user-defined commands or system commands.
- **Environment Variables**: Supports environment variable expansion.
- **Pipes**: Implements basic pipe functionality to chain commands together.
- **Built-in Commands**: Implements basic shell commands like `exit`, `cd`, and others.
- **Error Handling**: Graceful error handling for invalid commands or usage.

## Learning Objectives

- Gain a better understanding of how shells work.
- Learn how to implement basic command parsing and execution.
- Understand how environment variables and pipes work in a shell.
- Learn how to manage memory dynamically and handle user input effectively.

## Requirements

- **C Programming Language**: This project is written in C.
- **Operating System**: It works on Unix-like systems (Linux, macOS).
- **Libraries**: The standard C library is used, including basic I/O functions.

## Setup

To get started, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    $ git clone https://github.com/iamqaasim/simple_shell.git
    ```

2. Navigate to the project directory:
    ```bash
    $ cd simple_shell
    ```

3. Compile the program using `gcc`:
    ```bash
    $ gcc -Wall -Werror -Wextra -pedantic *.c -o shell
    ```

4. Run the shell:
    ```bash
    $ ./shell
  
## Usage

- After running the shell program, you can type commands just like in any Unix shell.
- The program supports:
  - Running external commands.
  - Built-in commands like `exit` and `cd`.
  - Basic pipe functionality (`|`).

The shell program is a simplified version of a Unix shell and is intended for educational purposes.
