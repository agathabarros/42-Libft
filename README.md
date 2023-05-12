# 42-Libft
This document provides information about the Libft project for 42 - Common Core, including a list of mandatory functions such as ft_isalpha, ft_isdigit, ft_strlen, and others. 

To build the library, simply run the following command in the repository's root directory:

Mandatory : `make`

Bonus Part: `make bonus`

This will generate the libft.a file, which can be linked to your C project.

# Mandatory Functions

### [Makefile](https://github.com/agathabarros/42-Libft/blob/master/Makefile)
The makefile is a file used to automate the compilation of programs into a project. It is composed of rules that specify the dependencies between files and the actions that must be followed to build the project.

### [Libft.h](https://github.com/agathabarros/42-Libft/blob/master/libft.h)
This is a header file for a C language library called libft, which is a library of common functions written for use in future projects. This header includes several function declarations as well as a structure that will be used for implementing the extra bonus functions.

## Part 1
### Character manipulation:

[ft_isalpha](https://github.com/agathabarros/42-Libft/blob/master/ft_isalpha.c): *Checks if a character is an alphabet character.*

[ft_isdigit](https://github.com/agathabarros/42-Libft/blob/master/ft_isdigit.c): *Checks if a character is a digit, specifically between 0 and 9.*

[ft_isalnum](https://github.com/agathabarros/42-Libft/blob/master/ft_isalnum.c): *Checks if the character is alphanumeric.*

[ft_isascii](https://github.com/agathabarros/42-Libft/blob/master/ft_isascii.c): *Checks whether a character is an ASCII character or not.*

[ft_isprint](https://github.com/agathabarros/42-Libft/blob/master/ft_isprint.c): *Check if the character can be printed.*

### String manipulation:
[ft_strlen](https://github.com/agathabarros/42-Libft/blob/master/ft_strlen.c): *Calculates the length of a given string.*

[ft_strlcpy](https://github.com/agathabarros/42-Libft/blob/master/ft_strlcpy.c): *Copy string from src to dest up to size.*

[ft_strlcat](https://github.com/agathabarros/42-Libft/blob/master/ft_strlcat.c): **

[ft_toupper](https://github.com/agathabarros/42-Libft/blob/master/ft_toupper.c): **

[ft_tolower](https://github.com/agathabarros/42-Libft/blob/master/ft_tolower.c): **

[ft_strchr](https://github.com/agathabarros/42-Libft/blob/master/ft_strchr.c): **

[ft_strncmp](https://github.com/agathabarros/42-Libft/blob/master/ft_strncmp.c): **

[ft_strnstr](https://github.com/agathabarros/42-Libft/blob/master/ft_strnstr.c): **

[ft_atoi](https://github.com/agathabarros/42-Libft/blob/master/ft_atoi.c): **

### Memory manipulation:
[ft_memset](https://github.com/agathabarros/42-Libft/blob/master/ft_memset.c):

[ft_bzero](https://github.com/agathabarros/42-Libft/blob/master/ft_bzero.c):

[ft_memmove](https://github.com/agathabarros/42-Libft/blob/master/ft_memmove.c):

[ft_memchr](https://github.com/agathabarros/42-Libft/blob/master/ft_memchr.c):

[ft_memcmp](https://github.com/agathabarros/42-Libft/blob/master/ft_memcmp.c):

### With malloc:
[ft_calloc](https://github.com/agathabarros/42-Libft/blob/master/ft_calloc.c):

[ft_strdup](https://github.com/agathabarros/42-Libft/blob/master/ft_strdup.c):

## Part 2

String manipulation:
[ft_substr](https://github.com/agathabarros/42-Libft/blob/master/ft_substr.c):

[ft_strjoin](https://github.com/agathabarros/42-Libft/blob/master/ft_strjoin.c):

[ft_strtrim](https://github.com/agathabarros/42-Libft/blob/master/ft_strtrim.c):

[ft_split](https://github.com/agathabarros/42-Libft/blob/master/ft_split.c):

[ft_strmapi](https://github.com/agathabarros/42-Libft/blob/master/ft_strmapi.c):

[ft_striteri](https://github.com/agathabarros/42-Libft/blob/master/ft_striteri.c):

[ft_putchar_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putchar_fd.c):

[ft_putstr_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putstr_fd.c):

[ft_putendl_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putendl_fd.c):

[ft_putnbr_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putnbr_fd.c):


## Bonus Part

/*Notion with code explanation [here](https://time-block-641.notion.site/Libft-8b3810011e254dc98a3ab4bc2c3bf7c8).*/
