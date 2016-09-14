Can find preconfigure VIM as IDE environment created by [Damian Ziobro on GitHub]
(https://github.com/xmementoit/vim-ide)

It contains preconfigured BASH script to install it on your Ubuntu (not tested on other OSes). In order to install vim-ide on Ubuntu, you need to do following steps:

back up your previous vimrc configuration
`cp $HOME/.vimrc $HOME/.vimrc.bak`
clone vim-ide repository to your HOME directory
`cd $HOME && git clone https://github.com/xmementoit/vim-ide`
install vim-ide in your system
`cd vim-ide && ./installVim.sh`
explore possibilities and plugins of vim-ide repository in $HOME/.vimrc and $HOME/.vim. Ex. open main.cpp file
`vim /tmp/main.cpp`
enjoy your work with vim-ide !
https://github.com/xmementoit/vim-ide