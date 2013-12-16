# vim-shortcuts

> vim gedoens

## Reset search highlighting

    set hlsearch!

## Select all text

    ggVG
## Convert split modes

To change two vertically split windows to horizonally split

    Ctrl-W t Ctrl-W K

Horizontally to vertically:

    Ctrl-W t Ctrl-W H

Explanations:

`Ctrl-W t` makes the first (topleft) window current `Ctrl-W K` moves the current window to full-width at the very top `Ctrl-W H` moves the current window to full-height at far left


## Multiline comment

First enable block visual mode

    Ctrl+V

Then select rows

    Shift+i

Enter comment char (i.e. # or //)

Press 

    ESC

It takes a second until the comments appear.
