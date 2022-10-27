# linux_system_functions
Recreating some of the most useful linux system functions in C.

## env.c

* On Unix systems, processes have access to environment variables that can influence the behavior
of programs. The global variable environ, declared as `extern char **environ;` points to an array of pointers to strings. 
The last pointer has the value `NULL`. By convention, the strings have the form `“NAME=VALUE”` and the names are often written using uppercase characters.
  
  * _Examples of environment variables are USER (the name of the current user), HOME (the current user’s home directory), or PATH (the colon-separated list of directories where the system searches for executables)_
