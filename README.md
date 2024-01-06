42cursus' ft_printf
Development repo for 42cursus' ft_printf project
For further information about 42cursus and its projects, please refer to 42cursus repo.

About · Usage · Useful Links
🗣️ About
This project is pretty straight forward. You will recode printf. Hopefully you will be able to reuse it in future project without the fear of being flagged as a cheater. You will mainly learn how to use variadic arguments.

🚀 TLDR: this project consists of coding a library that contains a simplified version (more
information below) of the printf function.
Mandatory
format specifiers - cspdiuxX%
🛠️ Usage
Requirements
The library is written in C language and thus needs the gcc compiler and some standard C libraries to run.

Instructions
1. Compiling the library

To compile the library, run:

$ cd path/to/ft_printf && make
2. Using it in your code

To use the library functions in your code, simply include its header:

#include "ft_printf.h"
and, when compiling your code, add the required flags:

-lftprintf -L path/to/libftprintf.a -I path/to/ft_printf.h
Third-party testers
printfTester
gavinfielder/pft
Mazoise/42TESTERS-PRINTF
HappyTramp/ft_printf_test
t0mm4rx/ftprintfdestructor
charMstr/printf_lover_v2
📌 Useful Links
C++ Reference - printf
Article: Secrets of “printf” (PDF)
MacOS documentation - printf
IEEE-754 Floating Point Converter
How does one print floats for ft_printf? - Stack Overflow - 42 Network
Printing Floating-Point Numbers
Printing Floating-Point Numbers Quickly and Accurately with Integers
What precisely does the %g printf specifier mean? - Stack Overflow
Notes
What is Variadic Functions?
Variadic function takes indefinite size arity and a variable number of arguments as a parameter. Situations that you do not know how many parameters pass the function.
what is ellipses (...)?
The ellipsis (...) is part of the C language and indicates that there are 0 or more optional arguments.
What is va_list?
What is va_start?
gets the address of the first argument.
What is va_arg?
dereference the block address and type cast it to the appropriate type. then goes to the next block of memory.
What is a "Type Descriptor"?
What is va_end?
Calling convensions!
https://www.youtube.com/watch?v=JHGTXM3oIs0
https://en.wikipedia.org/wiki/X86_calling_conventions
https://www.youtube.com/watch?v=F3XiH78erNM&t=1615s
notesrg

