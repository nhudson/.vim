.vim
====

My vim dot files. the `.vimrc` file is saved to [vimrc](https://github.com/nhudson/.vim/blob/master/vimrc).

Just run the following commands via terminal to get perfectly set up:

```console
$ cd ~/
$ git clone --recursive https://github.com/nhudson/.vim.git .vim
$ ln -sf $HOME/.vim/vimrc $HOME/.vimrc
$ cd $HOME/.vim
$ git submodule update --init
```

## Add plugins
To add in new plugins run the following commands.

```console
$ cd ~/.vim
$ git submodule add https://github.com/w0rp/ale.git bundle/ale
$ git submodule init
```

## Pathogen
The vim dot files make use of the excellent [Pathogen](https://github.com/tpope/vim-pathogen) runtime path manager to install plugins and runtime files into their own private directiories.

Currently using version 2.2 of Pathogen

## Plugins Used

* [github.com/martinda/Jenkinsfile-vim-syntax](https://github.com/martinda/Jenkinsfile-vim-syntax.git)
* [github.com/w0rp/ale](https://github.com/w0rp/ale.git)
* [github.com/pearofducks/ansible-vim](https://github.com/pearofducks/ansible-vim)
* [github.com/ctrlpvim/ctrlp.vim](https://github.com/ctrlpvim/ctrlp.vim.git)
* [github.com/Raimondi/delimitMate](https://github.com/Raimondi/delimitMate.git)
* [github.com/zchee/deoplete-go](https://github.com/zchee/deoplete-go.git)
* [github.com/Shougo/deoplete.nvim](https://github.com/Shougo/deoplete.nvim.git)
* [github.com/vivien/vim-linux-coding-style](https://github.com/vivien/vim-linux-coding-style.git)
* [github.com/scrooloose/nerdtree](https://github.com/scrooloose/nerdtree.git)
* [github.com/godlygeek/tabular](https://github.com/godlygeek/tabular.git)
* [github.com/xtal8/traces.vim](https://github.com/xtal8/traces.vim.git)
* [github.com/vim-airline/vim-airline](https://github.com/vim-airline/vim-airline.git)
* [github.com/vim-airline/vim-airline-themes](https://github.com/vim-airline/vim-airline-themes.git)
* [github.com/moll/vim-bbye](https://github.com/moll/vim-bbye.git)
* [github.com/ntpeters/vim-better-whitespace](https://github.com/ntpeters/vim-better-whitespace.git)
* [github.com/ap/vim-buftabline](https://github.com/ap/vim-buftabline.git)
* [github.com/crosbymichael/vim-cfmt](https://github.com/crosbymichael/vim-cfmt)
* [github.com/altercation/vim-colors-solarized](https://github.com/altercation/vim-colors-solarized.git)
* [github.com/tpope/vim-endwise](https://github.com/tpope/vim-endwise.git)
* [github.com/tpope/vim-five.git](https://github.com/tpope/vim-fugitive.git)
* [github.com/airblade/vimgutter.git](https://github.com/airblade/vim-gitgutter.git)
* [github.com/fatih/vim-go](https://github.com/fatih/vim-go.git)
* [github.com/fatih/vim-hclfmt](https://github.com/fatih/vim-hclfmt.git)
* [github.com/Yggdroot/indentLine](https://github.com/Yggdroot/indentLine.git)
* [github.com/lepture/vim-jinja](https://github.com/lepture/vim-jinja.git)
* [github.com/elzr/vim-json](https://github.com/elzr/vim-json.git)
* [github.com/plasticboy/vim-markdown](https://github.com/plasticboy/vim-markdown.git)
* [github.com/terryma/vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors.git)
* [github.com/fatih/vim-nginx](https://github.com/fatih/vim-nginx.git)
* [github.com/daltoad/vim-pug.git](https://github.com/digitaltoad/vim-pug.git)
* [github.com/hynek/vim-python-pep8-indent](https://github.com/hynek/vim-python-pep8-indent.git)
* [github.com/mhinz/vim-sayonara](https://github.com/mhinz/vim-sayonara.git)
* [fedorapeople.org/home/fedora/wwoods/public/vim-scripts.git](git://fedorapeople.org/home/fedora/wwoods/public_git/vim-scripts.git)
* [github.com/hashivim/vim-terraform](https://github.com/hashivim/vim-terraform.git)
* [github.com/cespare/vim-toml](https://github.com/cespare/vim-toml.git)
