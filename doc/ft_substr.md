# ft_substr

## Description
Allocates (with malloc(3)) and returns a substring from the string ’s’. The substring begins at index ’start’ and is of maximum size ’len’.

## Declaration 
```c
char *ft_substr(char const *s, unsigned int start, size_t len);
```

## Parameter 
- s: The string from which to create the substring. 
- start: The start index of the substring in the string ’s’. 
- len: The maximum length of the substring.

## Return 
- The substring. 
- NULL if the allocation fails.

---
- [Back to overwiew](Overview_about_function.md)
- [Back to main](/)
