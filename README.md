# Dotfiles

My personal dev environment.
Configs for my favourite tools.

## Stack

* **Shell** Zsh
* **Terminal Emulator** iTerm2  (Solarized Dark colour scheme)
* **Editor** VS Code (with vim keybindings)

## Structure

* `/git` Global rules, ignores, aliases
* `/tmux` Tmux config, keybindings, theme
* `/vscode` Extensions, formatting config, keybindings
* `/zsh` Customised shell prompt, requires omz

# Installation

To map these onto local config the recommended processs is via symlinks out of the folder after pulling the repo.

```bash
ln -sfn ~/dotfiles/zsh/.zshrc ~/.zshrc
ln -sfn ~/dotfiles/tmux/.tmux.conf
ln -sfn ~/dotfiles/git/.gitconfig ~/.gitconfig
ln -sfn ~/dotfiles/git/.gitignore_global ~/.gitignore_global
```

note that you'll need to manually pull in the profile for iterm2 if you choose to use mine.
