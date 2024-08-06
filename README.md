# dotfiles

Setup new machines with dotfiles.

## Prerequisites

Some dependencies to install the dotfiles.

### GNU STOW

* Linux (Debian/Ubuntu)

```bash
sudo apt update
sudo apt install stow
```

* Linux (Fedora/RHEL/CentOS)

```bash
sudo dnf install stow
```

* macOS

```bash
brew install stow
```

## Installation

```bash
git clone https://github.com/MikeGutty/dotfiles.git .dotfiles
cd .dotfiles
stow zsh # for zsh configuration
stow alacritty # for alacritty configuration
stow tmux # for tmux configuration
```
