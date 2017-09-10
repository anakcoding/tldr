# Info

- look up STRING in all indices of all manuals:

`info --apropos {{String}}`

- add DIR to INFOPATH:

`info -d {{Dir}}`

- remember user keystrokes in FILENAME:

`info  -d {{Filename}}`

- specify Info file to visit:

`info -f {{Filename}}`

- display this help and exit:

`info -h`

- go to node pointed by index entry STRING:

`info --index-search {{String}}`

- specify nodes in first visited Info file:

`info -n {{Filename}}`

- output selected nodes to FILENAME:

`info -o {{Filename}}`

-  output "raw" ANSI escapes (default):

`info -R`

-  output escapes as literal text:

`info --no-raw-escapes`

- read initial keystrokes from FILENAME:

`info --restore {{Filename}}`

- go to command-line options node:

`info -O`

- recursively output menu items:

`--subnodes`

- print physical location of Info file:

`info -w`

- use vi-like and less-like key bindings:

`--vi-keys`

- display version information and exit:

`--version`
