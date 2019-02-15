# Custom zsh

![iTerm2 Custom](iterm-custom.png)


**Resources**

- [Theme Material Design](material-design-colors.itermcolors)
- [Font Meslo LG L DZ Regular Nerd Font Complete](Meslo_LG_L_DZ_Regular_Nerd_Font_Complete.otf)
- [Source Code Pro Powerline Awesome Regular](SourceCodePro+Powerline+Awesome+Regular.ttf)
- [Source Code Pro for Powerline](Source_Code_Pro_for_Powerline.otf)


**Install**

```
brew update
brew cask install iterm2
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
brew install zsh-syntax-highlighting
brew install neofetch
brew install fontforge
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
```

> Instalation diretory **zsh-syntax-highlighting**: /usr/local/Cellar/zsh-syntax-highlighting/0.6.0/share/zsh-syntax-highlighting/

**Steps after all instalations**

- cp **.zshrc** to ~/ (see the paths and custom about your paths)
- Install the fonts: **Source Code Pro Powerline Awesome Regular** and **Font Meslo LG L DZ Regular Nerd Font Complete** (just double click on the files and click in install)
- Import **Theme Material Design** on iTerm2 (Preferences > Profile > Colors > Color Presets > Import...)
- Set the fonts on iTerm2 (Preferences > Profile > Text > Change Font > Select **SourceCodePro+Powerline+Awsome Regular** with size 14, after check **Use a different font non-ASCII text** and Change Font > Select **Meslo LG L DZ Regular Nerd Complete** with size 14)

### References
--------------

- [Andrea's config](https://github.com/bhilburn/powerlevel9k/wiki/Show-Off-Your-Config#andreas-config)
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [dotfiles by andrea](https://github.com/da-edra/dotfiles)
- [zsh-users](https://github.com/zsh-users)
- [iterm2-solarized](https://gist.github.com/kevin-smets/8568070)
