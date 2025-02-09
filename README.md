# Mini_Projects
A collection of small embedded system projects showcasing firmware development, peripheral interfacing, and real-time system design. Implementations include C/C++ code for microcontrollers, sensor integration, communication protocols (UART, SPI, I2C), and low-level hardware interactions.

1) Implement Shell in C
Overview
A simple Unix shell in C that reads, parses, and executes user commands. Supports built-in commands and launches external programs.

Features
Reads & executes user commands
Supports built-in commands:
cd – Change directory
help – Show available commands
exit – Exit shell
Executes external commands using execvp()
Uses fork() & waitpid() for process handling
APIs & Functions
Function Name	Description
lsh_read_command_line()	Reads user input
lsh_split_into_separate_commands()	Parses input into tokens
lsh_execute_commands()	Runs built-in or external commands
lsh_launch_commands()	Forks and executes processes
