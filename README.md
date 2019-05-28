# cmr-workstation-setup
A repository for the Clear My Record engineering team to collect shared workstation settings

## Getting started
1. First make sure you are fully up to date with macOS

1. Install [brew](https://brew.sh)

1. Run 
  ```bash
  cd [path/to/cmr-workstation-setup]
  brew bundle
  ```

## Shell Options

Depending on your team shell preference you can copy over the various configuration files for each shell into your home directory.

* ZSH
  An example .zshrc is available if the team prefers ZSH
  When using ZSH we use [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) to manage configuration. The recommended them is [Zagnoster](https://raw.githubusercontent.com/zaksoup/zotfiles/master/zagnoster.zsh-theme)
  Once you've installed oh-my-zsh and the .zshrc you can run `chsh -s /bin/zsh`
  Also recommended are [powerline fonts](https://github.com/powerline/fonts)
* BASH
  An example .bashrc and .bash-profile are available if the team prefers bash

## Iterm Configuration

* With Zagnoster
  Recommended colors are [Hybrid](https://raw.githubusercontent.com/w0ng/dotfiles/master/iterm2/hybrid.itermcolors)
