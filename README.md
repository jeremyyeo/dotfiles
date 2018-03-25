# Config Files

Contains config files for:

1. Vim
2. tmux

After cloning, move config files to user dir and source tmux config file:

    mv dotfiles/.vimrc ~ && tmux source ~/.tmux.conf

Then install the Vundle Vim plugin manager:

    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    vim +PluginInstall +qall
    
