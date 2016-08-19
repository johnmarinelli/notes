# sed

> sed -n -e 's/^\* \(.*\)/\1/p'

`-n`: filter lines that don't match a pattern

`/p` outputs only matched lines

#vim

`set fdm=manual`: sets fold creation to manual 

`ESC-zf`: creates a fold from highlighted region

`zo`: open fold under cursor

`zc`: close fold under curser

#emacs

`M-{>,<}`: go to to bottom/ top of buffer

`SPC <navigate> C-x t <string to insert> RET`: insert at beginning on multiple lines

### cider
`C-c M-n`:  switch to namespace of current buffer

`C-c C-k`: compile current buffer

`C-x C-c`: eval expression preceding point

`C-c M-o`: clear buffer

# network stuff
`sudo tcpdump -i any -s0 -vvv -A host $TARGET_HOST` listen to broadcasts from $TARGET_HOST
