## ALX Team Project  "Simple_Shell"
This is an ALX collaboration project on Shell. We were tasked to create a simple shell that mimics the Bash shell. Our shell shall be called hsh

## Language 

C language

Shell

Betty linter

## Requirement for project

All files are compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89

All files should end with a new line

A README.md file is mandatory

Betty style is used for checking using betty-style.pl and betty-doc.pl

Shell should not have any memory leaks

No more than 5 functions per file

All header files should be include guarded

## Description

hsh is a simple UNIX command language interpreter that reads commands from either a file or standard input and executes them.

## How hsh works

Prints a prompt and waits for a command from the user

Creates a child process in which the command is checked

Checks for built-ins, aliases in the PATH, and local executable programs

The child process is replaced by the command, which accepts arguments

When the command is done, the program returns to the parent process and prints the prompt

The program is ready to receive a new command

To exit: press Ctrl-D or enter "exit" (with or without a status)

Works also in non interactive mode

## Compilation

gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

## What we learned:

How a shell works and finds commands

Creating, cloaning, forking and working with processes

Executing a program from another program

Handling dynamic memory allocation in a large program

Pair programming and team work

Building a test suite to check our own code

## Authors
👤 Kerim Endris

## Cintributor
👤 Adeyemi Olusola
