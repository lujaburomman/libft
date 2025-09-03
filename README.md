📚 Libft

Libft is a custom C library that reimplements a variety of standard C library functions and additional utility functions. It serves as a foundational toolset for future projects in the 42 School cursus.

This project demonstrates memory management, string manipulation, and low-level C programming while strictly following 42 School rules.

🔹 Project Overview

The library is split into two parts:

Part 1 – Reimplementation of libc functions

You will recreate common C standard library functions with the ft_ prefix. Examples include:

Character checks: ft_isalpha, ft_isdigit, ft_isalnum, ft_isascii, ft_isprint

String manipulation: ft_strlen, ft_strchr, ft_strrchr, ft_strncmp, ft_strlcpy, ft_strlcat

Memory functions: ft_memset, ft_bzero, ft_memcpy, ft_memmove, ft_memchr, ft_memcmp

Conversion and case: ft_atoi, ft_toupper, ft_tolower

Memory allocation: ft_calloc, ft_strdup

All functions follow the man page behavior exactly and are written without external library dependencies.

Part 2 – Additional Utility Functions

These functions extend standard C functionality:

ft_substr → Extract a substring from a string

ft_strjoin → Concatenate two strings

ft_strtrim → Trim characters from beginning and end of a string

ft_split → Split a string by a delimiter

ft_itoa → Convert an integer to a string

ft_strmapi → Apply a function to each character of a string, returning a new string

ft_striteri → Apply a function to each character of a string in-place

File descriptor output functions:

ft_putchar_fd → Write a character

ft_putstr_fd → Write a string

ft_putendl_fd → Write a string with newline

ft_putnbr_fd → Write an integer
