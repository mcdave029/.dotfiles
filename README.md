# Development Setup

Personal backup of my development environment setup

## Getting Started
Download the repo and start symlinking all the configuration files in each steps if needed.

### Terminal
* Download [Ghostty](https://ghostty.org) (replaced iTerm2).
* Install [tmux](https://github.com/tmux/tmux) — `brew install tmux` (config is a lean `.tmux.conf`, no longer [Oh My Tmux](https://github.com/gpakosz/.tmux)).
* Install [TPM](https://github.com/tmux-plugins/tpm): `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`, then `prefix + I` inside tmux to install plugins.
* Symlink the configs:
  * `ln -sf $(pwd)/.tmux.conf ~/.tmux.conf`
  * `ln -sf $(pwd)/ghostty/config.ghostty ~/Library/Application\ Support/com.mitchellh.ghostty/config.ghostty`
* Install [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh).
* Install latest [vim](https://www.vim.org/) version.
* Install [Commitizen](https://eidson.info/post/using-conventional-commit-messages-globally) globally.
* Install a [Nerd Font](https://www.nerdfonts.com) for Non-ASCII glyphs (tmux status line uses them).

### iOS Development
* Install [Xcode](https://stackoverflow.com/a/10335943).
* Integrate [Xvim2](https://github.com/XVimProject/XVim2).

### Containerization
* Install [Docker](https://docs.docker.com/docker-for-mac/install/).

### Version Managers
* Install [rbenv](https://github.com/rbenv/rbenv) for ruby version manager.
* Install [nvm](https://github.com/nvm-sh/nvm) for node version manager.
* Optional [asdf-vm](https://asdf-vm.com/).

### VPN Tools
* Install [Forticlient](https://www.forticlient.com/downloads).
* Install [vnc viewer](https://www.realvnc.com/en/connect/download/viewer/macos/).

### Phoenix Elixir
* Install [Elixir](https://elixir-lang.org/install.html#macos).
* Install [Phoenix](https://hexdocs.pm/phoenix/installation.html).

### Apps
* Chrome
* Slack
* Spotify
* [Transmission](https://transmissionbt.com/download/)
* [SQLiteBrowser](https://sqlitebrowser.org/dl/)
