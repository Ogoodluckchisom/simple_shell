# Simple Shell

## Author:

[Ogoodluckchisom](https://github.com/Ogoodluckchisom)

## Synopsis
We have made a simple shell that can execute files found in the path, and handle
some built ins.

The format for entering a command is as follows:
ls (command) -la (arguments)

---

## Description
This version of a simple shell will execute commands that are found in the path
and some built ins. All output is written to stdout, this shell can work in both
interactive mode, and non-interactive mode.

##### Example

/tmp$ ls -l
total 0
/tmp$

## File list

| File name | Description |
| --- | --- |
| AUTHORS | authors of this project |
| README.md | this file |
| add_node.c | adds a node to the linked list used for the path |
| add_node_end.c | adds a node to the end of the linked list used for path |
| alias_fn.c | allowes the use of aliases |
| atoi_fn.c | alpha to int
| ch_dir.c | changes the current working directory |
| change_dir.c | changes the current working directory |
| conv_line.c | converts a line to a command for execve |
| echo_fn.c | allowes the use of echo function |
| exec_cmd.c | executes the command given to it |
| exit_fn.c | exits the program |
| free_av.c | frees the values contained in av |
| free_list.c | frees the linked list used for the path |
| get_current_dir.c | checks current directory for :/ |
| get_line.c | gets a line of input from the user |
| getcwd.c | gets the current working directory |
| getenv.c | gets the current working environment |
| help_fn.c | adds the help feature |
| helper.c | handles built ins such as cd |
| holberton.h | header contains libs, global vars, structs, func prototypes |
| itoa_fn.c | int to alpha
| ls_current_dir.c | prints the current working directory |
| man_1_simple_shell | the man page for this project |
| path_list.c | takes the path and makes it into a linked list |
| print_list.c | a debug file to print the contents of the linked list |
| realloc.c | reallocates memory for getline |
| search_file.c | searches the path for the given file |
| setenv.c | allows the setting of variables |
| setenv_fn.c | allows the settinf of variables |
| simple_shell.c | the main driver function |
| strcmp.c | compares two strings |
| strdup.c | duplicates a string |
| strlen.c | finds the length of a string |
| strstr.c | locates a substring |
| truc_spaces.c | truncates the leading white spaces of a command |
| unsetenv.c | unsets a variable |
| unsetenv_fn.c | unsets a variable |

## Compilation
All files where compiled on Ubuntu 14.04 LTS

All programs and functions were compiled with gcc 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic.
