# 0x16. C - Simple Shell
A simple shell project by Norris Selorm Bedzo and Jonathan Abayie Boahene


## Compilation

gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

This will compile all the '.c' files and change the output's name to 'hsh'.

## Template to test output:

```C:

$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$

```


### Function Prototypes:

Brief description of functions contained in project:

- _strcmpdir : compares strings to find dir.
- find_command : finds command to execute in path routes.
- charput : writes the character like putchar.
- place : similar to puts in C.
- _strlen : string length.
- str_concat : concatenate strings.
- lookforslash : identify if first char is a '/'.
- compareExit : checks if user typed exit.
- compareEnv : checks if user typed env.
- execute_proc : receives command and args from getline to be executed.
- identify_string : returns pointer with folder address.
- prompt : infinite loop with fork to keep prompt going.
- controlC: avoid program closing when pressing ctrl + c.
- main: initialize program.

## Authors
- Norris Selorm Bedzo | bedzon@ieee.org
- Jonathan Abayie Boahene | jonathanboahene@gmail.com
