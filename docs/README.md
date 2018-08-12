# NOOBS TERMINAL

## Overview
Noobs Terminal is a single-command installer that incorporates some of the wonderful terminal programs, packages, and configurations that are commonly installed together.   

Special thanks to all of the contributors and creators of the tools and configurations included.

![](docs/_media/preview.png)

What's included
---------------
| Feature | Description |
| --- | --- |
| [zsh](https://en.wikipedia.org/wiki/Z_shell) | a popular shell with features like completion, path correction, spelling correction, and more |
| [tmux](https://github.com/tmux/tmux) | terminal muxiplier allows you to manage multiple terminal sessions from a single window |
| [neovim](https://neovim.io/) | a project that seeks to aggressively refactor Vim |
| [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) | a framework for managing your zsh configuration |
| [vim-sensible](https://github.com/tpope/vim-sensible) | vim settings everyone can agree on  
| [tmux-sensible](https://github.com/tmux-plugins/tmux-sensible) | tmux settings everyone can agree on |
| [nord-tmux](https://github.com/arcticicestudio/nord-tmux) | An arctic, north-bluish clean and elegant tmux color theme |
| [nord-vim](https://github.com/arcticicestudio/nord-vim) | An arctic, north-bluish clean and elegant Vim color theme 
| [imp](https://github.com/aaronkjones/Imp) | My modified Imp theme by [igormp](https://github.com/igormp/Imp) | 

## Features
* Auto Completion
* Auto Suggestion
* Command Validation
* Spell Correction
* Themes
* Directory History
* Git 
* Aliases

![](docs/_media/zsh-autocompletion-suggestion.gif)

## Install
To install, run this command in your terminal:  
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/aaronkjones/noobs-term/master/noobs-term.sh)"`

## Setup
### Ubuntu

After installing, follow these steps.

* Press *Ctrl* + *a*, then *I* to load Tmux plugins
* In Gnome Terminal preferences, set Nord as your default profile
* Set an appropriate font (e.g. Inconsolata for Powerline)

> Note: You will have to log out and back in for Zsh to be set as the default shell. If you don't want to log out, enter *zsh*.

### OSX

* Press *Ctrl* + *a*, then *I* to load Tmux plugins
* In iTerm, set your color profile to Nord
* Set an appropriate font (e.g. Inconsolata for Powerline)

> Note: You will have to log out and back in for Zsh to be set as the default shell. If you don't want to log out, enter *zsh*.

## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md).