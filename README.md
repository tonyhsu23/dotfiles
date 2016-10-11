# Dotfiles

files includes:

- vimrc
- tmux.conf
- zsh-theme

## zsh-theme

- Symlink zsh file from your source path to `~/.oh-my-zsh/custom/filename.zsh-theme`

## vimrc

- Install [Vundle](https://github.com/VundleVim/Vundle.vim)
- Install [Pathogen](https://github.com/tpope/vim-pathogen)
- Install [Solarized Theme](http://ethanschoonover.com/solarized/vim-colors-solarized)
  - Add [color scheme](https://github.com/tomislav/osx-terminal.app-colors-solarized) to terminal

## tmux

- Install [Plugin](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard)
- [tmux copy and paste on OS X](https://robots.thoughtbot.com/tmux-copy-paste-on-os-x-a-better-future)

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
