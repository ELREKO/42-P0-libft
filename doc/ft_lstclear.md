# ft_lstclear

## Description
Deletes and frees the given node and every successor of that node, using the function ’del’ and free(3). Finally, the pointer to the list must be set to NULL.

## Declaration 
```c
	void ft_lstclear(t_list **lst, void (*del)(void *));
```

## Parameter 
- lst: The address of a pointer to a node. 
- del: The address of the function used to delete the content of the node.
## Return
- None

---
- [Back to overwiew](Overview_about_function.md)
- [Back to main](/)
