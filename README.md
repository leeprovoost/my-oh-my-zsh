my-oh-my-zsh
============

My own oh-my-zsh setup and config files

# Links
- http://www.iterm2.com/#/section/home
- http://ohmyz.sh/
- https://github.com/robbyrussell/oh-my-zsh
- https://github.com/robbyrussell/oh-my-zsh/wiki/Themes

# Installation
Install iTerm2 as a replacement for your OSX Terminal: http://www.iterm2.com

Using iTerm 2 install oh-my-zsh:
```
curl -L http://install.ohmyz.sh | sh
```

Download the powerline-fonts pack
```
git clone https://github.com/Lokaltog/powerline-fonts.git
```

Go to your iTerm2 Preferences panel and select a powerline font (I opted for 14pt Meslo LG S Regular for Powerline). Don't forget to set it for both the Font and Non-ASCII Font.

Download the Solarized colour theme from http://ethanschoonover.com/solarized

Open your iTerm2 Preferences panel again and load the Solarized Dark theme in your Colors tab.

Open your ZSH configuration file and add change the default ZSH_THEME to agnoster.
```
vi ~/.zshrc
```

Change whatever you want in the ZSH configuration file and don't forget to reload the file.
```
source ~/.zshrc
```




