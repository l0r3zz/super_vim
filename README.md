# super_vim
.vim directory with vimrc, plugins, .font dir with modified font - ready to load into your home_dir

This started when I found the great "Vim as IDE" repository by Jake Zimmerman : https://github.com/jez/vim-as-an-ide
While this is not a srict fork, most of the initial plugins I got from Jake. I do use vim-plug to manage my plug-ins, Jake's instructions talk about Vundle and he personally uses Pathogen.

To properly use this:

1. Unpack the .vim  entire directory into ~/.vim
2. Be sure to install a version of ctags
3. Install vim-plug:
```bash
    $ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
4. Then either soft link ~/.vimrc => ~/.vim/vimrc.vim  or copy vimrc.vim to your ~/.vimrc
5. Also for most beautiful results, add Menlo for Powerline (move the .fonts dir to your ~/.fonts dir)
6. Reload .vimrc and peform *:PlugInstall* to install the plugins
