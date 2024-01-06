# ft_printf - 42cursus

## Development Repository for 42cursus' ft_printf Project

For additional information about 42cursus and its projects, please refer to the [42cursus repository](https://github.com/42cursus).

### About

This project involves recoding the `printf` function. The primary goal is to create a library that contains a simplified version of `printf`. The intention is to enable reuse in future projects without the risk of being flagged as a cheater. This project primarily focuses on learning how to use variadic arguments.

#### TLDR

The project consists of coding a library containing a simplified version of the `printf` function.

### Mandatory

- Format specifiers: `c` `s` `p` `d` `i` `u` `x` `X` `%`

### Usage

#### Requirements

The library is written in the C language and, therefore, requires the gcc compiler and some standard C libraries to run.

#### Instructions

1. **Compiling the library**

   To compile the library, run:

   ```bash
   $ cd path/to/ft_printf && make

### Useful Links

- [C++ Reference - printf](http://www.cplusplus.com/reference/cstdio/printf/)
- [Article: Secrets of “printf” (PDF)](link_to_pdf_file.pdf)
- [MacOS documentation - printf](link_to_macos_printf_docs)
- [IEEE-754 Floating Point Converter](https://www.h-schmidt.net/FloatConverter/IEEE754.html)
- [How does one print floats for ft_printf? - Stack Overflow - 42 Network](https://stackoverflow.com/questions/22355899/how-does-one-print-floats-for-ft-printf-in-c-42-network)
- [Printing Floating-Point Numbers](https://floating-point-gui.de/printable/)
- [Printing Floating-Point Numbers Quickly and Accurately with Integers](https://www.cs.tufts.edu/comp/40/blog/accuracy-of-floating-point/)
- [What precisely does the %g printf specifier mean? - Stack Overflow](https://stackoverflow.com/questions/14585805/what-precisely-does-the-g-printf-specifier-mean)
- **Notes:**
  - **Variadic Functions:**
    - A variadic function takes indefinite size arity and a variable number of arguments as a parameter.
  - **Ellipses `(...):**
    - The ellipsis `...` is part of the C language and indicates that there are 0 or more optional arguments.
  - **va_list:**
    - The `va_list` gets the address of the first argument.
  - **va_start:**
    - `va_start` gets the address of the first argument.
  - **va_arg:**
    - Dereference the block address and type cast it to the appropriate type, then goes to the next block of memory.
  - **Type Descriptor:**
  - **va_end:**
  - **Calling Conventions:**
    - [Video: Calling Conventions](https://www.youtube.com/watch?v=JHGTXM3oIs0)
    - [Wikipedia: X86 Calling Conventions](https://en.wikipedia.org/wiki/X86_calling_conventions)
    - [Video: How the C Function Call Stack Works](https://www.youtube.com/watch?v=F3XiH78erNM&t=1615s)
  - **man stdarg:**
    - Information about `stdarg` can be found in the manual pages of your system. You can access it by running `man stdarg` in your terminal.
