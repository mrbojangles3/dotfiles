Installation:
	git clone git://github.com/mrbojangles3/dotvim.git


Create Symlinks:

	ln -s ~/dotfiles/vimrc ~/.vimrc
	ln -s ~/dotfiles/gvimrc ~/.gvimrc

Git Commands:
	git remote add origin https://github.com/mrbojangles3/dotvim.git
	git push -u origin master

If a change is made:
	git push -u origin master
	cd ~/.vim; git pull
