# vim-elm-syntax

## Features

1. Syntax highlighting
1. Automatic indentation

### Missing features

Compiling, linting, formatting and other features aren't included in this plugin.
Have a look at [elm-tooling/elm-vim](https://github.com/elm-tooling/elm-vim).

## Installation

- **Vim-Plug** (recommended): `Plug 'andys8/vim-elm-syntax'`and run `:PlugInstall`
- Vundle: `Plugin 'andys8/vim-elm-syntax'`
- NeoBundle: `NeoBundle 'andys8/vim-elm-syntax'`
- Pathogen: `cd ~/.vim/bundle && git clone https://github.com/andys8/vim-elm-syntax`

### Note about vim-polyglot

If you are using [vim-polyglot](https://github.com/sheerun/vim-polyglot), you need to disable its default elm plugin by adding `let g:polyglot_disabled = ['elm']` to your config file.

## Credits

This repository is a fork of [`ElmCast/elm-vim`](https://github.com/ElmCast/elm-vim).
All credits go to the authors of this repository.

- Joseph Hager
- [Contributors](https://github.com/elmcast/elm-vim/graphs/contributors) of elm-vim
- Other vim-plugins, thanks for inspiration (elm.vim, ocaml.vim, haskell-vim)

## License

Copyright © Joseph Hager. See `LICENSE` for more details.
