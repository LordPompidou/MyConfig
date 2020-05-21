# MyConfig

This project is where I keep all of my config and al of my installations so I can have my setup from anywhere and have a safe one.

## Getting Started
Each software and tools have its own part in this README as an explanation of what to do.


## Wallpaper links
[4 chan wallpaper general catalog](https://boards.4chan.org/wg/catalog)

## Bashrc
Save of bashrc in case I destroy mine by "accident"

## Oh My ZSH
Personal save of my zsh config file

To install configurationn do:

Replace your **~/.zshrc** by the zshrc file present in this repo.

Then run:
```
sudo apt install fonts-powerline
cd ~/.oh-my-zsh/themes
```

In **agnoster.zsh-theme**, comment line `prompt_context` in `build_prompt()`

Then run:
```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/zsh-users/zsh-syntax-highlighting

source ~/.zshrc
```

## Vim
`sudo apt install vim`

## Terminator
```
 sudo add-apt-repository ppa:gnome-terminator
 sudo apt-get update
 sudo apt-get install terminator
 ```
 
 ## Todoist
 Go to the [releases](https://github.com/KryDos/todoist-linux/releases) and download the latest deb file.
 Install it.
 
 ## Typora
 ```
 wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -

# add Typora's repository
sudo add-apt-repository 'deb https://typora.io/linux ./'
sudo apt-get update

# install typora
sudo apt-get install typora
```
## Sublime Text
Install the GPG key:
`wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -`

Ensure apt is set up to work with https sources:
`sudo apt-get install apt-transport-https`

Stable version channel:
`echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list`

Update apt sources and install Sublime Text
```
sudo apt-get update
sudo apt-get install sublime-text
```

## Spotify
`snap install spotify`

## Signal
```
curl -s https://updates.signal.org/desktop/apt/keys.asc | sudo apt-key add -
echo "deb [arch=amd64] https://updates.signal.org/desktop/apt xenial main" | sudo tee -a /etc/apt/sources.list.d/signal-xenial.list
sudo apt update && sudo apt install signal-desktop
```

## Pomotroid
Go to the [releases](https://github.com/Splode/pomotroid/releases) and download the latest deb file.
Install it.

## BitWarden
`sudo snap install bitwarden`

## Plex Media Player
Community Plex Media Player to download as AppImage from [here](https://knapsu.eu/plex/)
