# Shortcut cheatsheet for my [neovim](https://neovim.io/) config

### General

- `i` Insert mode
- `e` End of word
- `a` Insert after cursor
- `ESC` Go back to normal mode

### Navigation

- `h` Move cursor left
- `j` Move cursor down
- `k` Move cursor up
- `l` Move cursor right

### Buffers
- `ctrl + o` Opens previous buffer
- `ctrl + i` Opens next buffer

### Windows

- `C-w v` Split window vertically
- `C-w s` Split window horizontally
- `C-w w` Focus next window
- `C-w c` Close window
- `C-w o` Close all other windows
- `C-w 5 +` Increase vertical window size by 5
- `C-w 5 >` Increase horizontal window size by 5
- `C-w L` Move window far-right
- `C-w H` Move window far-left

### Terminal

- `:term` Open terminal in window
- `i` Insert mode in terminal
- `C-x` Exit insert mode

### fzf

- `ff` Search files
- `fb` Search open buffers
- `fs` Search all files

### Search inside file

- `/` Start searching.
- `Enter` Execute search
- `n` Go to next occurence

### NERDTree

- `ft` Toggle NERDTree
- `u` Move up a directory
- `C` Move down a directory

### Copy & Paste

- `yy` Yank current line
- `yy3` Yank 3 lines, starting at the line of the cursor position
- `dd` Cut current line
- `p` Paste below cursor
- `P` Paste above cursor

### Misc
- `:noa ...` Runs command without triggering autocmd, i.e. `:noa w` to save without formatting
