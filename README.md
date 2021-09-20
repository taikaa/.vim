### Installing

Just run the following commands via terminal to get perfectly set up:

```console
$ cd ~/
$ git clone --recursive https://github.com/jessfraz/.vim.git .vim
$ ln -sf $HOME/.vim/vimrc $HOME/.vimrc
$ cd $HOME/.vim
$ git submodule update --init
```

### Pathogen
The vim dot files make use of the excellent [Pathogen](https://github.com/tpope/vim-pathogen) runtime path manager to install plugins and runtime files into their own private directiories.

Currently using version 2.4 of Pathogen

## Contributing

### Using the `Makefile`

You can use the [`Makefile`](Makefile) to run a series of commands.

```console
$ make help
install                        Sets up symlink for user and root .vimrc for vim and neovim.
README.md                      Generates and updates plugin info in README.md.
remove-submodule               Removes a git submodule (ex MODULE=bundle/nginx.vim).
update-pathogen                Updates pathogen.
update-plugins                 Updates all plugins.
update                         Updates pathogen and all plugins.
```

## Plugins Used
* [github.com/altercation/vim-colors-solarized](https://github.com/altercation/vim-colors-solarized.git)
* [github.com/elzr/vim-json](https://github.com/elzr/vim-json.git)
* [github.com/plasticboy/vim-markdown](https://github.com/plasticboy/vim-markdown.git)
* [github.com/hashivim/vim-terraform](https://github.com/hashivim/vim-terraform.git)
* [github.com/stephpy/vim-yaml](https://github.com/stephpy/vim-yaml.git)