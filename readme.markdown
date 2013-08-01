#nocturne.vim
A dark, high-contrast colorscheme for Vim.

Nocturne: where your code shines like the moon and your interface
fades into the night. This is the result of my search for the perfect 
colorscheme: I made my own!

![Syntax Groups](sample/groups.png?raw=true)

This is my personal colorscheme, so colors may change as I see fit. That said,
I don't anticipate any major changes.

##Requirements
Currently, the colorscheme has been tested in gVim 7.3+. It also works in a
256-color terminal with the
[CSApprox](http://www.vim.org/scripts/script.php?script_id=2390)
plugin.

##Installation
I suggest that you use [vundle](http://github.com/gmarik/vundle) to manage
nocturne. Add

    Bundle 'euclio/vim-nocturne'

to your .vimrc and run `:BundleInstall` to install the necessary files.

If you'd rather install manually, download
[nocturne.vim](colors/nocturne.vim?raw=true) and copy the file into
`~/.vim/colors` on OSX or Linux. For Windows, copy the file into
`C:\Users\<username>\vimfiles\colors`.

After nocturne is installed, add `colorscheme nocturne` to your .vimrc to
enable it.

##Sample Images
###Python
![Python](sample/python.png?raw=true)

###Java
![Java](sample/java.png?raw=true)

###C
![C](sample/c.png?raw=true)
