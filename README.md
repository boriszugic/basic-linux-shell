# Basic Linux Shell

### Description

3000shell is a basic Linux shell program designed for educational purposes. It provides a simple command-line interface for executing commands, managing processes, and working with environment variables.

### Features

- Command execution: Run external programs and built-in commands.
- Process management: Support for running processes in the background.
- Environment variables: Manipulate environment variables and display their values.
- Customizable prompt: You can customize the shell prompt.
- Signal handling: Handle signals like SIGHUP and SIGCHLD.
- I/O redirection: Redirect standard output to files using `>` and `>>`.

### Organization

- `shell.c`: Main program file.

### Instructions

1. Compile the program: `gcc -o shell shell.c`
2. Run the shell: `./shell`
3. Use the shell to execute commands.
4. You can customize the shell prompt using the `MYPROMPT` environment variable.

### Built-in Commands

- `exit`: Exit the shell.
- `plist`: List running processes.
- `unset`: Unset a specified environmental variable.

### Issues/Limitations

- Limited support for built-in commands; additional built-ins like `cd` and `export` are not implemented.
- Error handling is basic; error messages may not be informative.

### Authors and Acknowledgement
1. Boris Zugic
   - Email: boriszugic123@gmail.com
   - Contribution: Design and implementation
2. Anil Somayaji
    - Email: soma@scs.carleton.ca
    - Contribution: Design