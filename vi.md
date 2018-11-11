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
h, j, k, l - left , down, up, right 
also the arrow keys should work in vim

### move by word :
* w - move to the beginning of the next word 
* e - move to the end of the word
* b - move to the beginning of the word
* combinations: 3w 5b - move 5 words back

### move to start or end of a line : 
0 - move to the start of the line
$ - move to the end of the line 

### move to start of the document
gg - move to start
G - move to end 

### move to a specific line 
line-nbr + G

## Basic editing
* o - insert new line and enter INSERT mode
* O - insert new line above and enter INSERT mode
* p - paste
* x - deletes one char on the right 
* X - deletes one char on the left
* r - replaces the character under cursor with a letter while in NORMAL mode 
* d - delete and copies the word/letter/line to be pasted later (so this is actually a cut operation)  
* dd - deletes (cuts) a line
* S - deletes a line and enters INSERT mode
* a - appends text 
* combinations : d2w deletes two words, 5dd - deletes the next 5 lines

## Visual Mode 
v - enter visual mode
move the cursor (which actually selects the text) 
do something with the selection : like d 

## Find text
f - find a character
find word under cursor - * and #
n - search text

# Vi tutorials
* Interactive vim online [https://www.openvim.com/]
