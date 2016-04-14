## Basic motions and commands

### Pen to the page

* i - Enter insert mode at cursor
* I - Enter insert mode at first non-blank character
* s - Delete character under cursor and enter insert mode
* S - Delete line and begin insert at beginning of same line
* a - Enter insert mode after cursor
* A - Enter insert mode at the end of the line
* o - Enter insert mode on the next line
* O - Enter insert mode on the above line
* C - Delete from cursor to the end of the line and begin insert

### Scanning the canvas

* h - backward
* j - down
* k - up
* l - forward

### Motions

* w - Forward to the beginning of the next word
* W - Forward to the beginging of the next WORD
* b - Backward to the next beginning of a word
* B - Backward to the next beginning of a WORD
* e - Forward to the next end of word
* E - Forward to the next end of WORD
* 0 - Move to the zeroth character of the line
* $ - Move to the last character of the line
* ^ - First non-blank character of the line


* [n]f< o > - Forward until (nth) (o) (Inclusive)
* [n]F< o > - Backward until (nth) (o) (Inclusive)
* [n]t< o > - Forward until (nth) (o) (Exclusive)
* [n]T< o > - Forward until (nth) (o) (Exclusive)

### Searching

* / - Forward
* ? - Backward
* \* - Word under cursor - forward(bounded)
* g* - Word under cursor - forward(unbounded)
* \# - Word under cursor - backward(bounded)
* g# - Word under cursor - backward(unbounded)
* n - Next result, forward
* N - Next result, backward
* gg -Back to the beginnig of the file
* shift-g - the end of the file

### Copy/Paste

* y - Yank. Example: yw (yank word)
* p - paste after cursor
* P - paste before cursor
* v - Visual selection

### Undoing

* u - undo stuff
* ctrl-r - redo stuff

### Save/Quit
* :w - save
* :q - quit
* :wq -save and quit
* :q! - quit and dont mind if it is saved


