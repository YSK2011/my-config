# my-config
My configuration files: zsh, vim, git, aliases

## Install

1. Install zsh
```
sudo aptitude install zsh
```

3a. LINUX: Install the config from this repo. WARNING: This removes anaconda and the current config.
```
(rm -Rf ~/.my-config ~/.zshrc ~/.vimrc ~/.zsh-syntax-highlighting ~/.oh-my-zsh ~/.tmux.conf && curl -L git.io/antigen > .antigen.zsh && git clone https://github.com/sbairedd/my-config.git ~/.my-config && ln -s ~/.my-config/.zshrc ~/.zshrc && ln -s ~/.my-config/.vimrc ~/.vimrc && ln -s ~/.my-config/tmux/tmux.conf ~/.tmux.conf  && source ~/.zshrc && pip install --upgrade autopep8 && rm -rf ~/.vim/bundle/Vundle.vim && git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim && vim +PluginInstall +qall && conda config --set changeps1 False && echo 'Installed with no errors :)') || echo 'E: something bad happened :('
```

3b. MACOS: Install the config from this repo. WARNING: This removes anaconda and the current config.
```
(rm -Rf  ~/.my-config ~/.zshrc ~/.vimrc ~/.zsh-syntax-highlighting ~/.oh-my-zsh ~/.tmux.conf && curl -L git.io/antigen > .antigen.zsh && git clone https://github.com/sbairedd/my-config.git ~/.my-config && ln -s ~/.my-config/.zshrc ~/.zshrc && ln -s ~/.my-config/.vimrc ~/.vimrc && ln -s ~/.my-config/tmux/tmux.conf ~/.tmux.conf  && source ~/.zshrc && pip install --upgrade autopep8 && rm -rf ~/.vim/bundle/Vundle.vim && git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim && vim +PluginInstall +qall && conda config --set changeps1 False && echo 'Installed with no errors :)') || echo 'E: something bad happened :('
```

4. Install misc stuff that requires sudo
```
sudo aptitude install libsource-highlight-common source-highlight vim-gnome vim-nox-py2 vim-gnome-py2 exuberant-ctags vim-autopep8 python-autopep8 xclip && sudo update-alternatives --config vim
```
