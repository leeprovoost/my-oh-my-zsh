# oh-my-zsh Setup

My own oh-my-zsh setup and config files

!https://github.com/leeprovoost/my-oh-my-zsh/blob/master/agnoster-theme.png!

(Image source: https://github.com/robbyrussell/oh-my-zsh/wiki/Themes) 

## Links
- iTerm2 replacement for OSX Terminal: http://www.iterm2.com/
- oh-my-zsh: http://ohmyz.sh/
- oh-my-zsh github page: https://github.com/robbyrussell/oh-my-zsh
- Solarized color theme: http://ethanschoonover.com/solarized
- Powerline patched fonts: https://github.com/Lokaltog/powerline-fonts

## Installation
Install "iTerm2":http://www.iterm2.com as a replacement for your OSX Terminal.

Use iTerm2 to install oh-my-zsh:
```
curl -L http://install.ohmyz.sh | sh
```

Download the powerline-fonts pack
```
git clone https://github.com/Lokaltog/powerline-fonts.git
```
(Or just get it from my github repo "here":https://github.com/leeprovoost/my-oh-my-zsh/blob/master/Meslo%20LG%20S%20Regular%20for%20Powerline.otf.)

Go to your iTerm2 Preferences panel and select a powerline font (I opted for 14pt Meslo LG S Regular for Powerline). Don't forget to set it for both the Font and Non-ASCII Font.

Download the Solarized colour theme from http://ethanschoonover.com/solarized.

Open your iTerm2 Preferences panel again and load the Solarized Dark theme in your Colors tab.

Open your ZSH configuration file and add change the default ZSH_THEME to agnoster.
```
vi ~/.zshrc
```

Change whatever you want in the ZSH configuration file and don't forget to reload the file.
```
source ~/.zshrc
```




