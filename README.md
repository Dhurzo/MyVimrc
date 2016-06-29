# MyVimrc

This is my personal .vimrc with some VIM plugins managed using Vundle


First of all if you are ***not*** using Debian please comment first line:

"runtime! debian.vim

and uncomment:

"Plugin 'scrooloose/syntastic' 

"Plugin 'valloric/youcompleteme'

If you are ***USING*** Debian:

Instructions to install these plugins with Debian:

apt-get install vim-syntastic

apt-get install vim-youcompleteme

vam install syntastic

vam install youcompleteme

***Instructions for all the other plugins:***

- Download the .vimrc file.
- cp Downloads/vimrc /home/user/.vimrc
- Install bundle with $ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
- Open the .vimrc file with vim ( vim .vimrc)
- Use the vim command to install plugins :PluginInstall

*** See the autoformat plugin documentation***
https://github.com/Chiel92/vim-autoformat

*** Changes ***
- Plugin  for Rust

Note: To see the NEERDtree you should type the comand :NERDTree


