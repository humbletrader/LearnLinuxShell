# Vi basic commands
* Insert Movde : i
* Normal Mode: ESC

## Basic Commands 
* Save :w
* Quit :q
* Force quit without saving :q!
* Undo : u
* Redo: CTRL+R

## Cursor Movement

### One character at a time: 
* the arrow keys 
* h, j, k, l - left, down, up, right 
* combinations: 
   * 3h - moves cursor 3 characters on the left
   * 5j - moves 5 lines down

### move by word :
* w - move to the beginning of the next word 
* e - move to the end of the word
* b - move to the beginning of the word
* combinations: 
   * 3w - move cursor after 3 words 
   * 5b - move 5 words back

### move to start or end of a line : 
0 - move to the start of the line
$ - move to the end of the line 

### move to start of the document
gg - move to start
G - move to end 

### move to a specific line 
line-nbr + G

## Basic editing
* i - insert characters at the current cursor position (this is also the trigger for INSERT mode)
* I - insert characters at the beginning of current line (INSERT mode)
* a - appends text after the cursor (INSERT mode) 
* A - append text at the end of the current line (INSERT mode)
* o - insert new line (INSERT mode)
* O - insert new line above (INSERT mode)
* p - paste
* x - deletes one char after the cursor
* X - deletes one char before the cursor
* r - replaces the character under cursor with a letter while in NORMAL mode 
* s - substitute for a character/text (enters INSERT mode)
* d - delete and copies the word/letter/line to be pasted later (so this is actually a cut operation)  
* dd - deletes (cuts) a line
* D - deletes characters until the end of the line
* S - substitude for a line (and enters INSERT mode)
* combinations : 
    * 5x - deletes 5 characters after the cursor 
    * d2w -  deletes two words 
    * 5dd - deletes the next 5 lines
    * dgg - deletes everything from cursor to the begining of the file
    * dG - deletes everything until the end of the file

## Visual Mode 
v - enter visual mode
move the cursor (which actually selects the text) 
do something with the selection : like d 

## Find text
/ - find the specified text
f - find a character
find word under cursor - * and #
n - go to next occurence 
N - go to previous occurence

## Entering INSERT mode (all of them mentioned above) 
* i - classic - isert at the current position
* I - insert at the beginning of current line
* a - append after current position
* A - append at the end of the current line
* s - substitute for the current character
* S - substitute for the current line

# Vi tutorials
* [Interactive vim online](https://www.openvim.com/)
* [tutorial](http://www.washington.edu/computing/unix/vi.html)
* [tutorial](http://vim.wikia.com/wiki/Tutorial)
