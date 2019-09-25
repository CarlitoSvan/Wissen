Exit Vim                    
  :q    quit                  
  :q!   (forced)                       
  :wq   save and quit                      
  ZZ                          
  
Move
<<<<<<< HEAD
  h     left (logical line)
=======
  h     left
>>>>>>> 5bc07c7e97cdf7fcb86ef5d7545c3b67cae68d4d
  j     down
  k     up
  l     right
  gj    down (vis. line)
  gg    back to top
  G     to the last line    
  31G   to the 31st line
  0     to first char of the line
  w     1 word forward 
  3w    3words forward
  W     1 word forward (excludes , () and so on)
  b     back to previous word
  B     -"- (exclude ,)
  e     to last char of a word
  E     -"- (exclude ,)
  f+""  forward to the char ""
  F+""  backwards to the char ""
  t+""  forward until the char ""
  T+""  backwards until the char ""
  

change mode
  esc     back to command/normal 
  i       editing
  v       visual
  A       end of the line + gets into insert mode
  s       deletes under cursor + gets into insert mode
  S       deletes whole line + insert line
  o       next line + create new line + insert mode
  O       previous line -"- 

edit
  x       delete/cut under cursor pos
  2x      delete 2char
  dw      delete word
  dd      delete line
  u       undo
  ctrl+r  redo
  p       paste in next line
  r+""    replace + letter you want it to replace it with
  ce      change till the end of the word and gets into insert-mode
  ($c      change/delete an entire line and gets into insert mode)
  C       change from cursor pos till end of line
  yw      yank word / copy word
  %       finds open and closed () or <> and so on 
  :w+ctrl+d  tells every command that is available with :w

search  
  /+ java search forward to "java"
  ?+ java search backwards to "java"
  n       next  
  N       previous     
  ctrl+o  back to where you came from 
  ctrl+i  forward to where you´ve been
  :%s/oldString/newString/g        search and replace old with new in entire document
  :3,9s/oldString/newString/g      everything between line 3 and 9 -"-
  -"-/gc                           -"- + asks yes or no if you want to change



