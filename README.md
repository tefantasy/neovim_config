# neovim_config

## Usage

1. Install [vim-plug](https://github.com/junegunn/vim-plug):

```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

2. Copy the file to ``~/.config/nvim/init.vim``.

3. Change the path in line 1 of `init.vim` to a directory that you wish to save the plugin files. 

4. Execute command ``:PlugInstall`` in nvim to install the plugins.
