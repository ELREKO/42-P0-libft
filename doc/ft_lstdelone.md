# ft_lstdelone

## Description
Takes as a parameter a node and frees the memory of the node’s content using the function ’del’ given as a parameter and free the node. The memory of ’next’ must not be freed.

## Declaration 
```c
	void ft_lstdelone(t_list *lst, void (*del)(void *));
```

## Parameter 
- lst: The node to free. 
- del: The address of the function used to delete the content.

## Return 
- None

---
- [Back to overwiew](Overview_about_function.md)
- [Back to main](/)
