# neuron.vim
Manage your [Zettelkasten](https://neuron.zettel.page/2011401.html) with the
help of [neuron](https://github.com/srid/neuron) in {n}vim.

![usage-photo](https://lh3.googleusercontent.com/pw/ACtC-3f5ub7ODWrnCYh-ZHDaBk84ZzBjLZ50W32Se4NRqy0kaBOJLGysG8HYYqhpo3hgoc8rABOOrxVqOlA3ut6yB-KGMPuZOI5XQ7D-1nllqCH5oRx28wbXmsOmO2rIdaJFUpTQNTiP-g-vt-i3IAfbwXjC=w1472-h1005-no?authuser=0)

## Requirements
- [neuron](https://github.com/srid/neuron)
- [fzf](https://github.com/junegunn/fzf.vim)
- [ripgrep](https://github.com/BurntSushi/ripgrep)

## Installation
### Using [vim-plug](https://github.com/junegunn/vim-plug)
```vim
Plug 'junegunn/fzf.vim'
Plug 'BurntSushi/ripgrep'
```
```vim
Plug 'ihsanturk/neuron.vim'
```

## Mappings
```vim
nm <m-z>           :call ZettelSearch()<cr>
nm <LocalLeader>zn :call ZettelNew()<cr>
nm <LocalLeader>zi :call ZettelSearchInsert()<cr>
nm <LocalLeader>zl :call ZettelLastInsert()<cr>
nm <LocalLeader>zo :call ZettelOpenUnderCursor()<cr>
nm <LocalLeader>zu :call ZettelOpenLast()<cr>
```
