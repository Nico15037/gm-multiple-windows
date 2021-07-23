# gm-multiple-windows
DISCLAIMER: This only works for TESTING - exported versions of your project won't open multiple windows

The dll files and original ExecuteShell script were NOT made by me - please contact me if you are/know the creator

As of now, there are two main functions:

mw_open_windows()
---------------------------
Opens two windows by default

It can open more, but all windows AFTER the 1st will share the same position and size

mw_open_windows_ext
---------------------------
Opens multiple windows

Needs two 2D arrays, one for positions and the other for sizes

For example:

_pos_ary[0][0] = x;

_pos_ary[0][1] = y;

_size_ary[0][0] = width;

_size_ary[0][1] = height;

This would set the position and size for the FIRST window

Continue adding to this for any more windows you want to open

If there's more you want to add, I'm open to PRs!
---------------------------

Possible ideas for the future:

---------------------------
Compatibility with .yyp project files that have a space

"project_name.yyp" - will work

"project name.yyp" - will NOT work as of now

---------------------------
Function that fills out part of an array made for mw_open_windows_ext

(Across/along the screen + has separation space between the windows)

---------------------------
Function that places windows based on a pre-made config

Examples:

![image](https://user-images.githubusercontent.com/40710958/126715510-78fc2e62-90a8-43b9-9c66-94922179470b.png)
