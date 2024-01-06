# ft_printf - 42cursus

## Development Repository for 42cursus' ft_printf Project

For further information about 42cursus and its projects, please refer to [42cursus repository](https://github.com/42cursus).

## About

This project is pretty straightforward. You will recode printf. Hopefully, you will be able to reuse it in future projects without the fear of being flagged as a cheater. You will mainly learn how to use variadic arguments.

### TL;DR

This project consists of coding a library that contains a simplified version (more information below) of the printf function.

## Mandatory

- Format specifiers: `c` `s` `p` `d` `i` `u` `x` `X` `%`

## Usage

### Requirements

The library is written in C language and thus needs the gcc compiler and some standard C libraries to run.

### Instructions

1. **Compiling the library**

    To compile the library, run:

    ```bash
    $ cd path/to/ft_printf && make
    ```

2. **Using it in your code**

    To use the library functions in your code, simply include its header:

    ```c
    #include "ft_printf.h"
    ```

    And, when compiling your code, add the required flags:

    ```bash
    -lftprintf -L path/to/libftprintf.a -I path/to/ft_printf.h
    ```

## Examples

Here are some examples demonstrating the usage of the `ft_printf` library:

### Basic Usage

```c
#include "ft_printf.h"

int main() {
    ft_printf("Hello, %s!\n", "world");
    ft_printf("This is a number: %d\n", 42);
    ft_printf("Character: %c\n", 'A');

    return 0;
}

