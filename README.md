# ft_printf - 42cursus

## Development Repository for 42cursus' ft_printf Project

For further information about 42cursus and its projects, please refer to [42cursus repository](https://github.com/42cursus).

## About

This project involves recoding the `printf` function. The goal is to create a library that contains a simplified version of `printf`. The intent is to allow for reuse in future projects without the fear of being flagged as a cheater. This project provides an opportunity to learn how to use variadic arguments.

### TL;DR

This project consists of coding a library that contains a simplified version of the `printf` function.

## Mandatory

- Format specifiers: `c` `s` `p` `d` `i` `u` `x` `X` `%`

## Usage

### Requirements

The library is written in the C language and thus needs the gcc compiler and some standard C libraries to run.

### Instructions

1. **Compiling the library**

   To compile the library, run:

   ```bash
   $ cd path/to/ft_printf && make
Using it in your code

To use the library functions in your code, simply include its header:

c
Copy code
#include "ft_printf.h"
And, when compiling your code, add the required flags:

bash
Copy code
-lftprintf -L path/to/libftprintf.a -I path/to/ft_printf.h
Third-party Testers
printfTester
gavinfielder/pft
Mazoise/42TESTERS-PRINTF
HappyTramp/ft_printf_test
t0mm4rx/ftprintfdestructor
charMstr/printf_lover_v2
Useful Links
C++ Reference - printf
Article: Secrets of “printf” (PDF)
MacOS documentation - printf
IEEE-754 Floating Point Converter
How does one print floats for ft_printf? - Stack Overflow - 42 Network
Printing Floating-Point Numbers Quickly and Accurately with Integers
What precisely does the %g printf specifier mean? - Stack Overflow
Notes
What is Variadic Functions?
What is ellipses (...)?
What is va_list?
What is va_start?
What is va_arg?
What is a "Type Descriptor"?
What is va_end?
Calling conventions!
Video: Calling Conventions
Wikipedia: X86 Calling Conventions
Video: How the C Function Call Stack Works
man stdarg

