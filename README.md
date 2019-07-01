# Virtuous-Editor
A minimalist text editor purely done in C and VT100 ASNI codes

No ncurses nothing, why? because it's simple, it can be built by any linux compiler, without any fiddling with make files or any other thing
Keep in mind this is a hoppyist project and not meant for commercial or actual use at all

# Key bindings
CTRL-S - save
CTRL-Q - quit
CTRL-F - find

Usage - ``virtuous <file name>``

# Syntax Highlighting
Currently there is syntax highlighting for C/C++, Python and Lua, other languages will come soon enough

# Pallete changing
Simply change the color values inside the ``editorSyntaxToColor`` function, adding syntax highlighting for special files is documented inside the file

# Building
Virtuous can be built with any C compiler for example
``gcc -o virtuous virtuous.c``
Recommended way of building it though for not getting any warnings is
``gcc -o virtuous virtuous.c -Wall -W -pedantic -std=c99``
For the program to be in your path simply do
``cp virtuous /usr/bin/``

# Preview
![](https://raw.githubusercontent.com/Gulkbag/Virtuous-Editor/master/Preview.PNG)
![](https://raw.githubusercontent.com/Gulkbag/Virtuous-Editor/master/Preview2.PNG)

# Credits
Thanks to ``Colin/C. Night`` for coming up with the pallete and name for this editor
