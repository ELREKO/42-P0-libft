# ft_striteri

## Description
Applies the function ’f’ on each character of the string passed as argument, passing its index as first argument. Each character is passed by address to ’f’ to be modified if necessary.

## Declaration
```c
void ft_striteri(char *s, void (*f)(unsigned int, char*));
```
## Parameter 
- s: The string on which to iterate. 
- f: The function to apply to each character.

## Return value
- None

---
- [Back to overwiew](Overview_about_function.md)
- [Back to main](/)
