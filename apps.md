# brew
## brew
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
## brew cask
```bash
brew install zsh zplug goenv rbenv mysql
brew cask install atom google-chrome alfred slack jetbrains-toolbox docker gyazo kindle vlc pomodone iterm2 tweeten 
```

## setup zsh and oh-my-zsh
```bash
% sudo vi /etc/shells
```
add `usr/local/bin/zsh`
```bash
% chsh -s /usr/local/bin/zsh
% curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
```
then replace .zshrc

## fix agnoster theme
```bash
% git clone git@github.com:CyberLight/agnoster.zsh-theme.git
```
copy agnoster.zsh-theme to ~/.oh-my-zsh/themes/agnoster.zsh-theme

## other tools
- todoist
