# force

A simple tool to navigate online source code in the terminal.
 
## dependancies

### dmenu or fzf or rofi
A fuzzy finder is used for navigation

### curl
Used for obvious reason

### awk
Used for scrapping

### vim
A text editor is used for displaing the code. 
It could be _less_ but i use vim.

## general thoughts

At this point the tool supports only golang stadard libraries.
Note that it is heavily coupled to golang.org/src html source structure!

Currently I'm working on github public repo's scrapping.

Any suggestions are welcome!

## Installation

No automatic installer nor dependancy checker exists yet.
Just place gosrc file somewhere into PATH, run it and fuzzy-find through the
library. To navigate back one level, use ESC.

Use the Fource!
