# Mr.Bo.Jangles DotVim

## Installation:
```bash
git clone --recurse-submodules git@github.com:mrbojangles3/dotvim.git ~/.vim
```

## Create Symlinks:
```bash
ln -s ~/.vim/dotfiles/vimrc ~/.vimrc
ln -s ~/.vim/dotfiles/gvimrc ~/.gvimrc
ln -s ~/.vim/dotfiles/tmux.conf ~/.tmux.conf
```

## Git Commands:
```bash
git remote add origin https://github.com/mrbojangles3/dotvim.git
git push -u origin master
```

## If a change is made:
```bash
git push -u origin master
cd ~/.vim; git pull
```

## Syncronizing Plugins:

Using [vundle](https://github.com/VundleVim/)
`vim +PluginInstall +qall`
