## vim modes
- normal
- insert
- visual
- visual line

### basic movement
```
h        -   Move left
j        -   Move down
k        -   Move up
l        -   Move right
$        -   Move to end of line
0        -   Move to beginning of line (including whitespace)

w        -   Move forward to next word, with cursor on first character (use W to jump by whitespace only)
b        -   Move backward to next word, with cursor on first character (use B to jump by whitespace only)

fc       -   Move cursor to next occurrence of character c on the current line. Use Fc to move backwards

/word    -   Search forward for word. Accepts regular expressions to search
?word    -   Search backwards for word. Accepts regular expressions to search
n        -   Repeat the last / or ? command
N        -   Repeat the last / or ? command in the opposite direction
```

### normal mode -> insert mode
```
i        -   Enter insert mode to the left of the cursor
a        -   Enter insert mode to the right of the cursor
I        -   Enter insert mode at first character of current line
A        -   Enter insert mode at last character of current line

o        -   Insert line below current line and enter insert mode
O        -   Insert line above current line and enter insert mode
```

### DELETION
```
x        -   Delete character forward (under cursor). use x do delete backwards (before cursor)
r        -   Replace single character under cursor, and remain in normal mode
dm       -   Delete in direction of movement m. For m, you can also use w, b, or any other variation
dd       -   Delete entire current line
```


