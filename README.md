# README for simple_shell project

## Compilation
All files in this repository should be compiled in the following way:

```gcc -Wall -Werror -Wextra -pedantic -std=gnu8 *.c -o hsh```

## Project requirements.
Allowed editors: ```vi, vim, emacs```.
All files will be compiled on Ubuntu 20.04 LTS.
Your C programs and functions will be compiled with gcc using the flags -Wall -Werror -Wextra -pedantic and -std=gnu8.
All your files should end with a new line.
A ```README.md``` file, at the root of the folder of the project is mandatory.
Your code should use the Betty style. It will be checked using ```betty-style.pl``` and ```betty-doc.pl```.
Your shell should not have any memory leaks.
No more than 5 functions per file.
All your header files should be include guarded.
Use system calls only when you need to.
Usage
Once executed, the compiled file will bring up a prompt that executes built-in commands with arguments.

./hsh
(mcpshell) ls -l


## Files
Every file contains the functions that will be used to work with the main file:

* shell.h: header file.

* shell.c: the main shell file, storage the main functions related to the shell itself

* string_functions.c: storage the string related functions

* path_hand.c: storage the handler 

* mem_handler.c : storage the memory handler function

## Authors
This program was written by:

Ibrahim Sserunkuuma (https://github.com/Ibrah44)
Yassine Boujarfaoui
