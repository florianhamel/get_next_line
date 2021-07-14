# get_next_line

Both new and old get_next_line versions.
A 42 project that consists in coding a function in order to read a file line by line.

Here are the 2 prototypes :

New: char	*get_next_line(int fd);

Old: int	get_next_line(int fd, char **line); (/!\ Doesn't get the '\n' at end of line and doesn't pass Norminette v3)