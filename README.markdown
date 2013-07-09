# Mr.Bo.Jangles DotVim

## Installation:
```bash
git clone git://github.com/mrbojangles3/dotvim.git ~/.vim
```

## Create Symlinks:
```bash
ln -s ~/.vim/dotfiles/vimrc ~/.vimrc
ln -s ~/.vim/dotfiles/gvimrc ~/.gvimrc
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
```bash
git submodule init
git submodule update
```

## Where I learned this:
http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/

@nelstrom really liking the book
