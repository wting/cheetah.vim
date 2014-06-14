# cheetah.vim

## Description

This is a vim plugin provides [HTML Cheetah](http://www.cheetahtemplate.org/) file detection and syntax highlighting. The syntax file was copied from
[cybermirror.org](http://vim.cybermirror.org/runtime/syntax/cheetah.vim).

## Installation

### Using [Vundle][v]

1. Add `Bundle 'wting/cheetah.vim'` to `~/.vimrc`
2. `vim +BundleInstall +qall`

*Note:* Vundle will not automatically detect Cheetah files properly if `filetype
on` is executed before Vundle. Please check the [quickstart][vqs] for more
details.

### Using [Pathogen][p]

1. `cd ~/.vim/bundle`
2. `git clone git://github.com/wting/cheetah.vim.git`

[p]: https://github.com/tpope/vim-pathogen
[v]: https://github.com/gmarik/vundle
[vqs]: https://github.com/gmarik/vundle#quick-start
