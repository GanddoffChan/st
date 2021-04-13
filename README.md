# st (suckless terminal)

Orig: [suckless terminal (st)](https://st.suckless.org/)

## functionality

Copy and paste: `alt-c` and `alt-v`

Change of colourscheme: edit config.h to change the 8 normal and 8 bright colours; remember to compile the programme again after editing

alpha (opacity) patch is not included because that is the job of a compositor (such as [picom](https://github.com/yshui/picom)

## added patches

Any size: allows st to resize to any pixel size, makes the inner border size dynamic, and centers the content of the terminal so that the left/right and top/bottom borders are balanced

Bold is not bright: makes bold text rendered simply as bold, leaving the color unaffected

Box draw: nicer graphic lines and blocks characters

Dynamic cursor color: swaps the colors of your cursor and the character you're currently on

Invert: invert the colours for a light theme with `alt-x`

Right click paste: pressing right-click pastes from the primary-selection

Scroll back: scroll back through terminal output using `alt-j` and `alt-k`; faster scrolls are done with `alt-d` and `alt-u`; mouse scrolls are also supported
