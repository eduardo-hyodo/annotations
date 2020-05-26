# Vim Study

## Motion

### Line
* 0   = Get to the start of the line
* $   = Get to the end of the line
* t   = until a character
* f   = find in the line
* o   = open new line below on insert mode
* O   = open new line above on insert mode

### Whole
* gg  = start of the doc
* G   = end of the doc
* H   = top of the page
* M   = middle of the page
* L   = bottom of the packages

---

## Command

### Solo
* x, delete with normal mode
* r, replace a character with normal mode
* s, delete with insert mode
* u, undo
* C-r, redo

### Multi command
* d, delete by motion with normal mode
* c, change by motion with insert mode
* y, yank(copy) by motion

### Direct Object
* iw in current word
* it in current xml/html tag
* i{ insider curly brackets

## Navigation

### Splits
* sp, horizontal Split
* vs, vertical Split

### Tabs
* :tabnew creates a new tab
* gt      go to next tab
* gT      go to previous tab
* :tabo   close all other tabs besides the active one

### Jumps
* Ctrl-o jump backwards
* Ctrl-i jump forwards

### Search
* /, search whole file
* n, next match
* N, previews match

### Spelling
* [s    preview spelling error
* ]s    next spelling error
* z=    suggestion of spelling
* 1z=   uses the first suggestion without the menu

## Move things
* \>>      Move identantion forwards
* \<<      Move identantion backwards
* =G       Adjust identantion wholde doc
* alt+j    Move line down
* alt+k    Move line up
