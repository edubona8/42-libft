<div align="center">
	<a href="https://www.42sp.org.br/">
		<img src="https://static.wixstatic.com/media/1b540d_3141ceec765a45f4954e1e725e536a72~mv2.png/v1/fill/w_148,h_50,al_c,q_85,usm_0.66_1.00_0.01/42sp_logo_preto.webp">
	</a>
</div>

<h1 align="center"> Libft </h1>
<h1 align="center">
<p align="center">This project aims to code a C library regrouping usual functions that we will use in the next projects of the course.</p>



<h2 align="center">
	Project develop for 42Cursus </a>
</h2>

<p align="center">
  	<a href="https://www.linkedin.com/in/eduardo-bonamico-viana-2b23b721b/">
    	<img alt="Linkedin" src="https://img.shields.io/badge/Eduardo Bonamico Viana-blue?style=flat&logo=Linkedin&logoColor=white" />
</p>

## List of Functions

### Functions from `<ctype.h>`

- [`ft_isalpha`](ft_isalpha.c)	- checks for an alphabetic character.
- [`ft_isdigit`](ft_isdigit.c)	- check for a digit (0 through 9).
- [`ft_isalnum`](ft_isalnum.c)	- checks for an alphanumeric character.
- [`ft_isascii`](ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [`ft_isprint`](ft_isprint.c)	- checks for any printable character.
- [`ft_toupper`](ft_toupper.c)	- convert char to uppercase.
- [`ft_tolower`](ft_tolower.c)	- convert char to lowercase.

### Functions from `<string.h>`

- [`ft_strlen`](ft_strlen.c)	- calculate the length of a string.
- [`ft_memset`](ft_memset.c)	- fill memory with a constant byte.
- [`ft_bzero`](ft_bzero.c)	- zero a byte string.
- [`ft_memcpy`](ft_memcpy.c)	- copy memory area.
- [`ft_memmove`](ft_memmove.c)	- copy memory area.
- [`ft_strlcpy`](ft_strlcpy.c)	- copy string to a specific size.
- [`ft_strlcat`](ft_strlcat.c)	- concatenate a string to a specific size.
- [`ft_strchr`](ft_strchr.c)	- locate character in a string.
- [`ft_strrchr`](ft_strrchr.c)	- locate character in a string.
- [`ft_strncmp`](ft_strncmp.c)	- compare two strings.
- [`ft_memchr`](ft_memchr.c)	- scan memory for a character.
- [`ft_memcmp`](ft_memcmp.c)	- compare memory areas.
- [`ft_strnstr`](ft_strnstr.c)	- locate a substring in a string.
- [`ft_strdup`](ft_strdup.c)	- creates a duplicate for the string passed as a parameter.

### Functions from `<stdlib.h>`
- [`ft_atoi`](ft_atoi.c)	- convert a string to an integer.
- [`ft_calloc`](ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

### Non-standard functions
- [`ft_substr`](ft_substr.c)	- returns a substring from a string.
- [`ft_strjoin`](ft_strjoin.c)	- concatenates two strings.
- [`ft_strtrim`](ft_strtrim.c)	- trims the beginning and end of a string with a specific set of chars.
- [`ft_split`](ft_split.c)	- splits a string using a char as parameter.
- [`ft_itoa`](ft_itoa.c)	- converts a number into a string.
- [`ft_strmapi`](ft_strmapi.c)	- applies a function to each character of a string.
- [`ft_striteri`](ft_striteri.c)	- applies a function to each character of a string.
- [`ft_putchar_fd`](ft_putchar_fd.c)	- output a char to a file descriptor.
- [`ft_putstr_fd`](ft_putstr_fd.c)	- output a string to a file descriptor.
- [`ft_putendl_fd`](ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [`ft_putnbr_fd`](ft_putnbr_fd.c)	- output a number to a file descriptor.
