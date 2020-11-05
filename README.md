# vim-cheatsheet
The list of commands on vim which I often use 
~~~
:q -> quit 
:wq -> save and quit 
:q!-> quit and dont save the file 
:w -> save changes and not quit 
when in command mode 
j-> takes the curson down
k-> takes the cursor up 
l-> takes the cursor left 
h-> takes the curson right 
i-> to go into the insert mode 
when in insert mode you can type whatever you want 
esc -> takes you back to the command mode 
command made 
dd-> deletes the whole line 
G-> to go down (very bottom of the file)
gg -> to go back up 
{ -> to go the blocks of code 
} -> to go down the blocks of code 
*number*j-> takes you number lines down 
u-> to undo 
ctrl r -> to redo 
.-> to do the last command again 
yy-> to copy a line of code 
p-> to paste it below 
P -> to paste it above 
V-> drops you into visual mode (visual mode allows you to select the group
	and you can visually see whatever you have selected 
	-you can use any movement command here 
	-when you have it selected you can do delete paste copy stuff on it 
o-> to insert a line and puts to inside insert mode 
d}- deletes the entire block of code 
w-> takes the cursor to the next word in the line 
b-> takes the cursor to the previous word in the line 
:*line number* -> takes you to that line number 
:0 -> to the top 
0 -> takes you to the very beginning of the line 
^ -> takes you to the first word of the line 
0w -> emulates the behavior of ^ 
t*goto character*-> takes you to a specific character in line 
f -> does the same as t 
	the only difference is that f takes you to the character and t takes you 
	one to the left
f*the character*; -> goes through all the instances of *the character* in the line 
cw -> change word (deletes and specific word and takes you in insert mode) 
dw -> to delete a word 
D-> to delete the rest of the line 
C-> deletes the rest of the line and puts you in insert mode 
ct*change until character* -> deletes the line until that character and
	puts you in insert mode 
dt*delete until character*-> deletes the line until that character but 
	doesn't puts you in insert mode 
* -> to go to the other instance of the same word 
A -> takes to the very end of the line and puts you in insert mode 
x-> deletes whatever character the cursor is on 
~ -> swaps the case 
	lowercase -> uppercase 
	uppercase-> lowercase 
. -> redoes the last thing you do (probably the most useful command) 
r-> replaces the letter (ONE)
R-> replaces a bunch of letters 
> -> indents code  
< -> back indent 
q*key to save the recording to* -> macros 
	saves whatever you do that key; tap q again to quit the recording 
	now to use the macros just type @*the key* 
~~~ 
:)
