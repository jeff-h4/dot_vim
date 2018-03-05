# dot_vim
.vim folder for my vim setup

# Setup
1. Clone the repo into your home directory -- ~/dot_vim
2. Execute
  % ln -s ~/dot_vim/vimrc ~/.vimrc
3. Clone Vundle by executing:
  % git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
4. Launch Vim and in command mode, enter :PluginInstall
5. We need to install solarized. Execute:
  $ cd ~/.vim/bundle
  $ git clone git://github.com/altercation/vim-colors-solarized.git
  $ ln -s ~/.vim/bundle/vim-colors-solarized/colors/solarized.vim ~/.vim/colors/solarized.vim

At this point, it should just work. Hopefully.
