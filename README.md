_Printf Project
Creating my  printf function that produces output according to a format.

This repository includes my version of the printf function, the basic and main functions.
Requested by ALX School.

Description
The printf function prints a format control string of different data types on the standard output, its roots are in the C programming language, it is a functional way to produce a precise output format for printing numerical values or ASCII characters from format specifiers that have been passed on in the argument.

Prototype
This _printf function produces output according to a format:

int _printf(const char *format, ...);

Formats
flag	function
%c	print a single character
%s	print a string
%d	print a integer as a signed decimal (base 10) number
%i	print same as "d", integer in base 10

file	description
main.h	Contain the struct and prototypes to the _printf function
man_3_printf	Contain the man page of the _printf function with all its specifications
_printf.c	Contain the main function of the _printf

Author
- Donald Peters
