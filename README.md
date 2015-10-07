# super_vim
.vim directory with vimrc, plugins, .font dir with modified font - ready to load into your home_dir

To properly use this:

1. Unpack the .vim  entire directory into ~/.vim
2. Be sure to install a version of ctags
3. Install vim-plug:
```bash
    $ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
4. then either soft link ~/.vimrc => ~/.vim/vimrc.vim  or copy vimrc.vim to your ~/.vimrc
5. also for most beautiful results, add Menlo for Powerline (move the .fonts dir to your ~/.fonts dir )
