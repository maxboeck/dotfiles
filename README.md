# Dotfiles for ZSH

A collection of settings based on mathias bynens dotfiles, customized for use with Oh-my-Zsh. Used to set up a new stock version mac and get my development environment up and running.

## Contents

### .dotfiles
* .aliases: helpful shortcuts and commands
* .brewfile: install binaries and OSX Apps via Homebrew
* .curlrc: Configuration for ```curl``` command
* .exports: export some variables, sourced in .zshrc
* .gitconfig: git configuration (duh)
* .global-gitignore: global file excludes for git
* .hushlogin: remove logininfo when starting a new shell
* .osx: system defaults for OSX (Yosemite / El Capitan)
* .path: extend ```$PATH``` in here, sourced in .zshrc
* .screenrc: disable startup message in new shell
* .wgetrc: Configuration for ```wget``` command
* .zshrc: ZSH Main Profile

### settings

the ```settings``` folder contains configuration for Sublime Text 3, the ST Package Manager, My Custom ZSH Theme and color scheme. (Chris Kempsson's Base 16).

## Installation

Just Copy the dotfiles to your home directory ```cd ~```   

#### Install ZSH and Oh-my-Zsh:
```bash
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

#### Install Homebrew:
```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Install Binaries and OSX Apps:
```bash
brew bundle ~/.brewfile
```

#### Customize OSX Defaults
```bash
source ~/.osx
```
