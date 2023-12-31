# TEAM PROJECT : Simple Shell

In this project we implement a simple UNIX command interpreter.

## Requirements
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- Your shell should not have any memory leaks
- All your header files should be include guarded
- Your code should use the Betty style

## More Info
### Output
- Unless specified otherwise, your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.
- The only difference is when you print an error, the name of the program must be equivalent to your argv[0].

### List of allowed functions and system calls
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- getpid (man 2 getpid)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)

## Accepted Build in Commands
| Command	| Description		|
| ------------- | ----------------------- |
| exit | - The command to exit the shell. <br/>- Usage : exit status (where status is an integer used to exit the shell). | 
| setenv | - The command to initialize a new environment variable, or modify an existing one. <br/>- Usage : setenv VARIABLE VALUE |
| unsetenv | - The command to remove an environment variable. <br/>- Usage : unsetenv VARIABLE |
| env | - The command to print the current environment variables. |
| cd | - The command to change the working directory. <br/>- Usage : cd <DIRECTORY> |

## Commands
This simple shell can:
- Handle simple command with or without arguments.
- Determine the path of the command entered without path.
- Handle the “end of file” condition (Ctrl+D).
- Display the prompt again each time a command has been executed.

# Copyright
Authors : Hajar EL ABDELLAOUI <[ELABDELLAOUI-HAJAR](https://github.com/ELABDELLAOUI-HAJAR)>
