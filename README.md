# dot_vim
Vim configuration file and dependencies

Steps to get set up with this pre-configured vim environment (Sept. 2016)
Clone repository

Move contents of newly downloaded /dot_vim to ~/.vim

Move "dot_vim_file" to "/.vimrc". Change "no compatible" to "nocompatible" at the top of ~/.vimrc.

Clone and set up Vundle with "$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim". See - https://github.com/VundleVim/Vundle.vim.

source ~/.vimrc

vim +PluginInstall +qall


You're good to go.
