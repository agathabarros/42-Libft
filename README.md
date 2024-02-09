# 42-Libft
<p align="center">
  <img src="https://github.com/agathabarros/42-project-badges/blob/main/badges/libftm.png"/>
</p>

## *Grade: 125 / 100*
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

[ft_strlcat](https://github.com/agathabarros/42-Libft/blob/master/ft_strlcat.c): *Appends the src string to the end of the dst string.*

[ft_toupper](https://github.com/agathabarros/42-Libft/blob/master/ft_toupper.c): *Convert lowercase letters to uppercase*

[ft_tolower](https://github.com/agathabarros/42-Libft/blob/master/ft_tolower.c): *Converts uppercase letters to lowercase.*

[ft_strchr](https://github.com/agathabarros/42-Libft/blob/master/ft_strchr.c): *Searches for the first occurrence of the character c in the string pointed to by s*

[ft_strrchr](https://github.com/agathabarros/42-Libft/blob/master/ft_strrchr.c): *Searches for the last occurrence of the character c in the string pointed to by s.*

[ft_strncmp](https://github.com/agathabarros/42-Libft/blob/master/ft_strncmp.c): *Compares the first n characters of s1 and s2 memory.
Return < 0, s1 is less. return > 0, s2 is less. Return = 0.*

[ft_strnstr](https://github.com/agathabarros/42-Libft/blob/master/ft_strnstr.c): *Finds the first substring (little) in a string(big) with limited length(len).*

[ft_atoi](https://github.com/agathabarros/42-Libft/blob/master/ft_atoi.c): *Converts String to integers.*

### Memory manipulation:

[ft_memset](https://github.com/agathabarros/42-Libft/blob/master/ft_memset.c): *Copies the character c to the first n characters of the string pointed to by s.*

[ft_bzero](https://github.com/agathabarros/42-Libft/blob/master/ft_bzero.c): *Erases the data in the first n bytes of memory from the location pointed to by s and writes zeros in their place.*

[ft_memcpy](https://github.com/agathabarros/42-Libft/blob/master/ft_memcpy.c): *Copies n characters from src memory to dest memory.*

[ft_memmove](https://github.com/agathabarros/42-Libft/blob/master/ft_memmove.c): *Copies n characters from src to dest, but for blocks of overlapping memory, memmove() is a safer approach than memcpy()*

[ft_memchr](https://github.com/agathabarros/42-Libft/blob/master/ft_memchr.c): *Searches for the first occurrence of the character c in the first n bytes of the string pointed to by s. Returns a pointer to the byte corresponding.*

[ft_memcmp](https://github.com/agathabarros/42-Libft/blob/master/ft_memcmp.c): *Compares the first n bytes of memory s1 and memory s2. Return < 0, s1 is less. return > 0, s2 is less. Return = 0.*

### With malloc:
[ft_calloc](https://github.com/agathabarros/42-Libft/blob/master/ft_calloc.c): *Allocates the requested memory and returns a pointer to it. Calloc, unlike Malloc, sets the allocated memory to zero.*

[ft_strdup](https://github.com/agathabarros/42-Libft/blob/master/ft_strdup.c): *Function returns a pointer to a new string which is a duplicate of the string s. Returns a pointer to a string (created with malloc), which is a duplicate of the string pointed to by s.*

## Part 2

String manipulation:

[ft_substr](https://github.com/agathabarros/42-Libft/blob/master/ft_substr.c): *Function returns the substring of a given string between two given indices.*

[ft_strjoin](https://github.com/agathabarros/42-Libft/blob/master/ft_strjoin.c): *Allocates memory and returns a new string, which is the result of concatenating 's1' and 's2'.*

[ft_strtrim](https://github.com/agathabarros/42-Libft/blob/master/ft_strtrim.c): *Allocates (with malloc(3)) and returns a copy of ’s1’ with the characters specified in ’set’ removed from the beginning and the end of the string.*

[ft_split](https://github.com/agathabarros/42-Libft/blob/master/ft_split.c): *Allocates memory and returns an array of strings obtained by dividing 's' using the 'c' character as the delimiter. The array must end with a NULL pointer*

[ft_itoa](https://github.com/agathabarros/42-Libft/blob/master/ft_itoa.c): *Allocates memory and returns a string representing the integer received as an argument. Negative numbers must be handled.*

[ft_strmapi](https://github.com/agathabarros/42-Libft/blob/master/ft_strmapi.c): *Applies the function ’f’ to each character of the string ’s’* to create a new string (with malloc(3)) resulting from successive* applications of ’f’.*

[ft_striteri](https://github.com/agathabarros/42-Libft/blob/master/ft_striteri.c): *Applies the function ’f’ on each character of the string passed as argument, passing its index as first argument. Each character is passed by address to ’f’ to be modified if necessary.*

[ft_putchar_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putchar_fd.c): *The function outputs the character 'c' to a specified file descriptor using the write function, similar to the ft_putchar function, but with the option to choose the file descriptor.*

[ft_putstr_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putstr_fd.c): *The function outputs the string to a specified file descriptor using the write function, similar to the ft_putstr function, but with the option to choose the file descriptor.*

[ft_putendl_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putendl_fd.c): 

[ft_putnbr_fd](https://github.com/agathabarros/42-Libft/blob/master/ft_putnbr_fd.c):


## Bonus Part

[ft_lstnew](https://github.com/agathabarros/42-Libft/blob/master/ft_lstnew.c):
    *Add a new node and initialize next to null. Allocates (with malloc(3)) and returns a new node.
    The member variable ’content’ is initialized with the value of the parameter ’content’. The variable ’next’ is initialized to NULL.*
    
[ft_lstadd_front](https://github.com/agathabarros/42-Libft/blob/master/ft_lstadd_front.c):
  *Adds a new node to the beginning of the list.*

    
[ft_lstsize](https://github.com/agathabarros/42-Libft/blob/master/ft_lstadd_front.c):
   *Counts the number of nodes in a list.*

[ft_lstlast](https://github.com/agathabarros/42-Libft/blob/master/ft_lstlast.c):
  *Returns the last node of the list*
    
[ft_lstadd_back](https://github.com/agathabarros/42-Libft/blob/master/ft_lstadd_back.c):
   *Adds the node ’new’ at the end of the list*
    
[ft_lstdelone](https://github.com/agathabarros/42-Libft/blob/master/ft_lstdelone.c):
 *Takes as a parameter a node and frees the memory of the node’s content using the function ’del’ given as a parameter and free the node. The memory of ’next’ must not be freed*
    
[ft_lstclear](https://github.com/agathabarros/42-Libft/blob/master/ft_lstdelone.c):
  *Deletes and frees the given node and all successors to that node, using the 'del' and free function. The pointer to the list must be set to NULL.*
  
[ft_lstiter](https://github.com/agathabarros/42-Libft/blob/master/ft_lstdelone.c):
   *Iterates the list ’lst’ and applies the function ’f’ on the content of each node.*
 
[ft_lstmap](https://github.com/agathabarros/42-Libft/blob/master/ft_lstdelone.c):
  *Add a new node and initialize next to null. Allocates (with malloc(3)) and returns a new node.
The member variable ’content’ is initialized with the value of the parameter ’content’. The variable ’next’ is initialized to NULL.*


## ft_printf

## get_next_line

/*Notion with code explanation [here](https://time-block-641.notion.site/Libft-8b3810011e254dc98a3ab4bc2c3bf7c8).*/
