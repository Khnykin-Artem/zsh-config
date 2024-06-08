# Setup oh-my-zsh

## Install Oh My Zsh

`sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

## Clone github repository

`cd ~/` <br>
`git clone https://<TOKEN>@github.com/Khnykin-Artem/zsh-config.git` <br>
`sudo mv ~/zsh-config/* ~/` <br>
`sudo rm -rf ~/zsh-config`

## Fonts

`sudo mv ~/code-new-roman /usr/share/fonts`

## Plugins

**1.** `sudo pacman -S exa` <br>
**2.** `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k` <br>
**3.** `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting` <br>
**4.** `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions` <br>
**5.** `git clone https://github.com/wting/autojump.git` <br>
       `cd autojump` <br>
       `./install.py` 

## Finally
`source ~/.zshrc`

