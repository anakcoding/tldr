# Info

> Folowing instructions for show info

- Look up STRING in all indices of all manuals:

`info --apropos {{String}}`

- Add DIR to INFOPATH:

`info -d {{Dir}}`

- Remember user keystrokes in FILENAME:

`info  -d {{Filename}}`

- Specify Info file to visit:

`info -f {{Filename}}`

- Display this help and exit:

`info -h`

- Go to node pointed by index entry STRING:

`info --index-search {{String}}`

- Specify nodes in first visited Info file:

`info -n {{Filename}}`

- Output selected nodes to FILENAME:

`info -o {{Filename}}`

-  Output "raw" ANSI escapes (default):

`info -R`

-  Output escapes as literal text:

`info --no-raw-escapes`

- Read initial keystrokes from FILENAME:

`info --restore {{Filename}}`

- Go to command-line options node:

`info -O`

- Recursively output menu items:

`--subnodes`

- Print physical location of Info file:

`info -w`

- use vi-like and less-like key bindings:

`--vi-keys`

- Display version information and exit:

`--version`
