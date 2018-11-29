# Vim Reference Card
Useful commands and tips explained in the simpliest way.

# Vim Modes:
Normal - Default mode mostly used to delete, find and format files.  
Insertion - Used to edit a file.  
Command - Used to run commands (normally using :).  
Visual - Used like selection, in visual mode the words are highlighted.

# Vim structure:
A file in Vim is divided with rows and columns.

# Navigation
h - Move to left.  
j - Move to down.  
k - Move to up.  
l - Move to right.  

w - Move to the first character of the next word.  
W - 

e - Move to the last character of the word.  
E -

b - Move back to first character of the word.  
B - 

0 (zero) - Move to the beggining of the line.  
$ - Move to the end of the line.  

gg - Move to the first line of file.  
G (Shift + g) - Move to the end of file.

H - Move to the first line on the screen.  
M - Move to the middle line on the screen.

# Edition
a - Go to the insertion mode after the cursor.  
A - Go to the insertion mode after last character of the line.  

i - Go to the insertion mode before the cursor.  
I - Go to the insertion mode before the first character of the line.  

o - Create a new line below.  
O - Create a new line above.  

u - Like CTRL + Z  
U - 

# Searching  

f - Find the first occurrence from left to right.  
F - Find the first occurrence from right to left.  

t - Find  
T - Find  

, (comma) - Go to the next occurrence.  
; - Go to the previous occurence.  

*(asterisk) -   
#(hashtag) -  

# Replace
:%s/word-to-replace/word-to-be-replaced/ - Replace all occurrences.  
r - Replace the character in the cursor.  
~ - Uppercase or downcase the character.  

# Deleting  
dd - Delete the entire line.  
d$ - Delete to the cursor and final of line.  
D - Delete to the cursor and final of line.  

x - Delete the character in the cursor.  
X - Delete like backspace.  

# Commands  
wq - Save and close the file.  
wq! -

x - Save and close the file (like wq).  

q -  
q! -  
qa - Close without save all files opened.  
wqa - Save and close all files opened.  

:set nu - Show line numbers in the left side.  

# * Useful commands:  

cw -  
ci{ -  
123gg -   

yyp -   

_Useful reference guides:_  
https://www.vim-adventures.com (In my opinion, the best way to study Vim).
