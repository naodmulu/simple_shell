
This is a simple shell in C language which is done by two coders 
It can be a command-line interface –the one we will build- or graphical user interface, like regular software such as Windows Office.

Compilation This simple shell is compiled with:

gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

Output This program have exact same output as sh as well as the exact same error output. The only difference is when it prints an error, the name of the program is equivalent to argv[0].
