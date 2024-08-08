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

### Tmux

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

## Installation configuration

```bash
git clone https://github.com/MikeGutty/dotfiles.git .dotfiles
cd .dotfiles
stow zsh # for zsh configuration
stow alacritty # for alacritty configuration
stow tmux # for tmux configuration
```

## After Installation configuration

> For correct operation of the configuration, follow these steps

### Tmux

For tmux only need to install the plugins after installing tmux.

1. Init a session with tmux

```bash
tmux new -s session_name
```

2. Press `prefix` + <kbd>I</kbd> (capital i, as in **I**nstall) to fetch the plugin.

3. The prefix is definited in the `~/.tmux.conf` file and in this case the prefix its <kbd>ctrl</kbd> + <kbd>Space</kbd>
