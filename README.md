# dotfiles

My configuration files for my set up. I use ZSH with [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh).

Clone repo

```sh
git clone git@github.com:CEOehis/dotfiles.git ~/.dotfiles
```

Create the symlinks in the relevant directories to the configuration files.

```sh
ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
ln -s ~/.dotfiles/aliases.zsh ~/.oh-my-zsh/custom/aliases.zsh # This assumes you have ohmyzsh setup already
```

Then install the software listed in the Brewfile

```sh
brew bundle --file ~/.dotfiles/Brewfile # Assumes you have Homebrew installed already
```
