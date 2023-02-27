# nvim setup

https://www.youtube.com/watch?v=w7i4amO_zaE

## lua config location

`~/.config/nvim`

## Customization 

#### Remap

> `vim.g.mapleader = " "`. Space as the leader 

*leader* pv :arrow_right: `:Ex` 

#### Plugin Manager and Fuzzy Finder

**Plugin Manager*#

Packer.nvim

https://github.com/wbthomason/packer.nvim

**Fuzzy Finder**

telescope.nvim

https://github.com/nvim-telescope/telescope.nvim

#### Color Scheme

https://github.com/rose-pine/neovim


#### TreeSitter

What is tree-sitter?
https://github.com/tree-sitter/tree-sitter

Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

General enough to parse any programming language
Fast enough to parse on every keystroke in a text editor
Robust enough to provide useful results even in the presence of syntax errors
Dependency-free so that the runtime library (which is written in pure C) can be embedded in any application


#### Harpoon




## Vim Recaps

1. `vim` on a directory
   
   1) use `Enter` to go into or go back dirs
   2) to create a file, press `%`
   3) to create a folder, press `d`
   4) when inside a file, press `:Ex` to back to dirs browsing
  
2. Format a block of code
 
   1) Visual mode to select the content
   2) press `=` to format it


3. Inside a file control mode
   
   `:so` to source a file
   
   `C` to delete everything after and enter modification mode
   
   
