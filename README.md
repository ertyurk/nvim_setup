# nvim_setup


1. Install Nvim

```
brew install neovim
```

2. Create a new folder 

```
mkdir ~/.config/nvim
```

3. copy init.vim inside of newly created folder `nvim` in previous step
4. Install VimPlugin
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
5. open init.vim from new folder and run :PlugInstall
