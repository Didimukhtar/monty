# 0x19. C - Stacks, Queues - LIFO, FIFO
## Description

This is a collaborative project between Toluwani Ajibare and Al-Mukhtar Jamilat Ladidi who are both students in the ALX Africa software engineering.

This is an introduction to Stacks and Queues in C - programming language.

# Monty

`monty` is an interpreter of Monty ByteCodes files, which is a scripting language just like Python.

## About the Monty language
This is a language that contains specific instructions to manipulate data information (stacks or queues), where each instruction (*called opcode*) is sended per line. Files which contains Monty byte codes usually have the `.m` extension.

Example (`file.m`):
```bash
$ cat file.m
# Pushing element to the stack
push 0
push 1
push 2
# Printing all elements
pall
push 3
push 4
pop
# Rotating the stack to the bottom
rotr
pall
rotl
# Setting FIFO
queue
push 5
# Setting LIFO
stack
push 5
$
```

## Usage
To compile all files

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=c89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You allowed to use a maximum of one global variable
- No more than 5 functions per file
- You are allowed to use the C standard library
- The prototypes of all your functions should be included in your header file called monty.h
- Don’t forget to push your header file
- All your header files should be include guarded
- You are expected to do the tasks in the order shown in the project

## Compilation & Output
Your code will be compiled this way:
> $ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
- Any output must be printed on stdout
- Any error message must be printed on stderr

## Technologies
* Interpreter was written with C language
* C files are compiled using `gcc 4.8.4`
* C files are written according to the C90 standard
* Tested on Ubuntu 14.04 LTS


## Contributors
1. ToluwaniAJ [Gmail](mailto:toluwaniajibare@gmail.com)
2. Didimukhtar [Gmail](mailto:Jamilatmukhtar2014@gmail.com)
