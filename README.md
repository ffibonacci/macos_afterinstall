# macos afterinstall
## Brew
Install brew:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
sudo xcode-select --install
```
Set PATH for bash/zsh</br>
```
echo 'PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile
echo 'PATH="/usr/local/bin:$PATH"' >> ~/.zshrc
```
Check is everything okey</br>
```
brew doctor
```
### wget
```
brew install wget
```
## iTerm2
Install:
```
brew cask install iterm2
```
Settings:</br>
Set hot-key `iTerm Launch` to open and close the terminal to `command + option + i`</br>
Download [iTerm schemes(Themes)](https://github.com/mbadolato/iTerm2-Color-Schemes/tree/master/schemes)</br>
Install fonts:</br>
```
brew tap homebrew/cask-fonts && brew cask install font-source-code-pro
```
Set fonts to Source Code Pro (12/14pt)</br>
**Install [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)**</br>
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
Install **tree**</br>
```
brew install tree
```
## Git
Install:
```
brew install git
```
Check version:
```
git --version
```
Settings:
```
git config --global user.name "Name"
git config --global user.email "email@"
```
## VSCode
Install:
```
brew cask install visual-studio-code
```
## Python
Install pyenv:
```
brew install pyenv
echo 'eval "$(pyenv init -)"' >> ~/.zshrc
exec $SHELL
pyenv install --list
pyenv global 3.9.0
pyenv rehash
```

## Java
```
brew install openjdk
```
## Heroku
```
brew install heroku/brew/heroku
heroku update
```
## Apps
[Atom](https://atom.io/)</br>
[Transmission](https://transmissionbt.com/)</br>
[The Unarchiver](https://theunarchiver.com/)</br>
[VLC](https://www.videolan.org/vlc/index.html)</br>
[Opera](https://www.opera.com/ru)</br>
[Idea Intellij](https://www.jetbrains.com/idea/download/#section=mac)</br>
[PyCharm](https://www.jetbrains.com/pycharm/download/#section=mac)</br>
[Tor Browser](https://www.torproject.org)</br>
[VS Codium](https://vscodium.com)

## Firewall
### Free, open source
[Lulu Firewall](https://objective-see.com/products/lulu.html)
### $
[Little Snitch](https://www.obdev.at/products/littlesnitch/index.html)
