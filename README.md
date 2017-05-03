# nocturne.vim

A dark, high-contrast colorscheme for Vim.

![Syntax Groups](sample/groups.png?raw=true)

This is my personal colorscheme, so colors may change as I see fit. That said,
I don't anticipate any major changes.

## Requirements

Nocturne works in gvim by default.

If you wish to use nocturne in a terminal, you will either need to either:

* Provided you have a recent version of vim and a true-color terminal, add `set
   termguicolors` in your `.vimrc`.

* Use the [CSApprox] plugin.

## Installation

I suggest that you use [vim-plug] to manage nocturne. Add

    Plugin 'euclio/vim-nocturne'

to your `.vimrc` and run `:PlugInstall` to install the necessary files.

If you'd rather install manually, download [nocturne.vim][nocturne-raw] and copy
the file into `~/.vim/colors` on OSX or Linux. For Windows, copy the file into
`C:\Users\<username>\vimfiles\colors`.

After nocturne is installed, add `colorscheme nocturne` to your `.vimrc` to
enable it.

## Sample Images

### Python
![Python](sample/python.png?raw=true)

### Java
![Java](sample/java.png?raw=true)

### C
![C](sample/c.png?raw=true)

[CSApprox]: http://www.vim.org/scripts/script.php?script_id=2390
[vim-plug]: http://github.com/junegunn/vim-plug
[nocturne-raw]: colors/nocturne.vim?raw=true
