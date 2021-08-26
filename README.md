![](https://github.com/Ele4327/Test/blob/main/Recourses/Shell.png)

👋 Hello Devs
# Simple Shell

Hello and Welcome to our Holberton Simple Shell project.
In this repository you will find our own simple shell, developed by software developers in progress.

For those who dont know a shell is a program that presents a command line interface which allows you to control your computer using commands entered with a keyboard instead of controlling graphical user interfaces (GUIs) with a mouse/keyboard combination.

For a more specific explanation, we invite you to see our manual: man_1_simple_shell

# Features

- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- Your shell should not have any memory leaks
- No more than 5 functions per file
- All your header files should be include guarded
- Use system calls only when you need to

List of allowed functions and system calls:

- [ ] access
- [ ] chdir
- [ ] close
- [ ] closedir
- [ ] execve
- [ ] exit
- [ ] _exit
- [ ] fflush
- [ ] fork
- [ ] free
- [ ] getcwd
- [ ] getline
- [ ] getpid
- [ ] isatty
- [ ] kill
- [ ] malloc
- [ ] open
- [ ] opendir
- [ ] perror
- [ ] read
- [ ] readdir
- [ ] signal
- [ ] stat (__xstat)
- [ ] lstat (__lxstat)
- [ ] fstat (__fxstat)
- [ ] strtok
- [ ] wait
- [ ] waitpid
- [ ] wait3
- [ ] wait4
- [ ] write



## Output

Your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.
The only difference is when you print an error, the name of the program must be equivalent to your argv[0] (See below)

Example SH:
```
Example of error with sh:

$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$
```

Same error with your program hsh:
```
$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$
```
## Installation:

There is two ways: Compilation and Execution and Make

## Compilation and Execution




# How this works:

## Main Functions

## Subfunctions

## FlowChart:

![](https://github.com/Ele4327/simple_shell/blob/main/RECURSES/Basic_Shell_Flowchart.png)

## Tests



