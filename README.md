
## Printf

This project implements a custom version of the standard printf() function. The goal of this project is to replicate the behavior of printf() using a custom function called ft_printf() and to handle a specified set of format specifiers, while adhering to specific implementation requirements.

The function prototype is as follows:

```bash
  int ft_printf(char const *, ...);
```




## Project requirements

- Allowed functions: malloc, free, write, va_start, va_arg, va_copy, va_end.
- The ar command must be used to create the library; the use of libtool is prohibited.


## Implemented Format Specifiers

The ft_printf() function should handle the following format specifiers:

- %c – Prints a single character.
- %s – Prints a string.
- %p – Prints a void * pointer in hexadecimal format.
- %d – Prints a signed decimal integer (base 10).
- %i – Prints an integer in base 10.
- %u – Prints an unsigned decimal integer (base 10).
- %x – Prints a lowercase hexadecimal integer (base 16).
- %X – Prints an uppercase hexadecimal integer (base 16).
- %% – Prints the percentage symbol %.
## Learning Objectives:

Building printf provided the opportunity to:

- Gain proficiency in working with variadic functions (va_start, va_arg, va_end).
- Develop the ability to identify format specifiers and handle them with dedicated functions for better code organization.
- Learn how to create and manage static libraries in C using the ar tool.