0-strcat.c a function that concatenates two strings. Prototype: char *_strcat(char *dest, char *src); This function appends the src string to the dest string, overwriting the terminating null byte (\0) at the end of dest, and then adds a terminating null byte. Returns a pointer to the resulting string dest
1-strncat.c  a function that concatenates two strings. Prototype: char *_strncat(char *dest, char *src, int n); The _strncat function is similar to the _strcat function, except that it will use at most n bytes from src; and src does not need to be null-terminated if it contains n or more bytes. Return a pointer to the resulting string dest
2-strncpy.c a function that copies a string.
3-strcmp.c a function that compares two strings.
4-rev_array.c  a function that reverses the content of an array of integers.
5-string_toupper.c  a function that changes all lowercase letters of a string to uppercase.
6-cap_string.c  a function that capitalizes all words of a string.
7-leet.c a function that encodes a string into 1337.