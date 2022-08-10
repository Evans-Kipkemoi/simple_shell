# Sinbash Simple Shell



### Project details
-----
Welcome to the `Sinbash Simple Shell` project!! This program is a simple shell that can be compiled and launched from the command line. ALX Software Engineering project for low-level programming specifically C language.

### How to Compile | Invocattion
---------------
Usage: Sinbash is started withthe standard input connected to the terminal. To stat, compile all .c files located in this repository using

````
gcc -Wall -Werror -Wextra -pedantic *.c -o sinbash ./sinbash
````

Sinbash is allowed to be invoked interactively and non-interactively. 
If Sinvash is invoked with standard input not connected to a terminal, it reads and executes received commands in order.

### Syntax
-----
This shell follows the familiar syntax for any other shell.

### Testing

```
$ ./sinbashs
^.^
^.^ exit

```

### Builtin Commands
-----
This shell supports a variety of commands:

`alias` - create or list an alias

`cd` - change directory

`env` - list the current environment variables

`exit` - exit the shell

`history` - display the command history for the current shell session

`setenv` - sets an environment variable

`unsetenv` - unsets an environment variable

```
^.^ help <builtin command>
```



### Authors
---
[Evans Kipkemoi](https://github.com/Evans-Kipkemoi)
---
[Jerry Ngetich](https://github.com/Ngetich31801)

### More Information
-----

Sinbash is a simple shell unix command interpreter that is part of the alx low level programming module at Alx School and is intended to emulate the basics sh shell. All the information given in this README is based on the sinbash and bash man (1) pages.

