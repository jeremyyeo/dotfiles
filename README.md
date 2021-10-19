## Config Files

Contains config files for:

1. Vim
2. tmux

After cloning, move config files to user dir and source tmux config file:

    mv dotfiles/.vimrc ~ && mv dotfiles/.tmux.conf ~ && tmux source ~/.tmux.conf

Then install the `spacegray` color scheme and the Vundle Vim plugin manager:

    git clone git://github.com/ajh17/Spacegray.vim ~/.vim/pack/vendor/start/Spacegray
    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    vim +PluginInstall +qall

