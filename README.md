# Setup oh-my-zsh

## Install Oh My Zsh

`sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

## Clone github repository

`cd ~/`
`git clone https://<TOKEN>@github.com/Khnykin-Artem/zsh-config.git`
`sudo mv ~/zsh-config/* ~/`
`sudo rm -rf ~/zsh-config`

## Fonts

`sudo mv ~/code-new-roman /usr/share/fonts`

## Plugins

**1.** `sudo pacman -S exa`
**2.** `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`
**3.** `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
**4.** `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
**5.** `git clone https://github.com/wting/autojump.git`
       `cd autojump`
       `./install.py` 

## Finally
`source ~/.zshrc`

