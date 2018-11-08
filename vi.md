# Vi basic commands
Insert Movde : i
Normal Mode: ESC

# Basic Commands 
Save :w
Quit :q
Force quit without saving :q!

Undo : u
Redo: CTRL+R

# Cursor Movement

### One character at a time: 
h, j, k, l - left , down, up, right 

### move one word :
 w - move to the beginning of the next word 
 e - move to the end of the word
 b - move to the beginning of the word

### move to start or end of a line : 
0 - move to the start of the line
$ - move to the end of the line 

### move to start of the document
gg - move to start
G - move to end 

### move to a specific line : line-nbr + G

## Find text
f - find a character
find word under cursor - * and #
n - search text

## Basic editing
0 - insert new line and enter INSERT mode
O - insert new line above and enter INSERT mode
p - paste
d - delete (see combinations) and copies the word/letter to be pasted later 
R - replace the character under cursor when in NORMAL mode 

Combinations : 
d2w - deletes 2 words 

## Visual Mode 
v - enter visual mode
move the cursor ( which actually selects the text) 
do something with the selection : like d 
