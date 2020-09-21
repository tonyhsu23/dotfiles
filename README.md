# Dotfiles

files includes:

- zsh
  - zshrc
  - zlogin
  - theme
     - solarized
     - tomorrow
  - functions (g)
- vim
  - vimrc
  - javascript.vim
- tmux
  - tmux.conf
  - tat
- git
  - gitconfig
- git_template
  - hooks
- ack
  - ackrc

## zsh

### zsh-theme

- Symlink zsh file from your source path to `~/.oh-my-zsh/custom/<filename>.zsh-theme`

## vim

### vimrc

- Install [Vundle](https://github.com/VundleVim/Vundle.vim)
- Install [Pathogen](https://github.com/tpope/vim-pathogen)
- Install [Solarized Theme](https://ethanschoonover.com/solarized/)
  - Add [color scheme](https://github.com/tomislav/osx-terminal.app-colors-solarized) to terminal
- Install [The Silver Searcher](https://github.com/ggreer/the_silver_searcher)
- Add [Tomorrow Theme](https://github.com/chriskempson/tomorrow-theme/tree/master/OS%20X%20Terminal)

### javascript.vim

- Symlink this file from your source path to `~/.vim/after/ftplugin/javascript.vim`

## tmux

### plugin

- Install [tmux copy and paste on OS X plugin](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard), [reference](https://robots.thoughtbot.com/tmux-copy-paste-on-os-x-a-better-future)

### tat
  - make a bin directory at home path, and symlink `tat` file
  - add `/bin` path to your login shell file
     - e.g. `export PATH="$HOME/bin:$PATH"`, add to `.zshrc`

## For ubuntu to work...

1. tmux

  tmux version should be higher than 2.0

2. vim

  File Type Indentation Setting

  - Put ftplugins in `~/.vim/after/ftplugin/`

  Set the following lines to configure colors

  - let g:solarized_termcolors=256
  - set t_co=256
  - set t_ut=

3. zsh

  set terminal as xterm-256color
