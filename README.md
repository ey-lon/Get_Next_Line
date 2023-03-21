# Get_Next_Line
| prototype |
| --------- |
| char  *get_next_line(int fd); |

This function returns a single line from a given file descriptor.

If called in a loop, get_next_line returns the entire contents of a file, line by line until it reaches the end of the file.

It can be compiled specifying any buffer size.
