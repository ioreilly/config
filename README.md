#  Overview

An assortment of configuration files to get new hosts development ready.

# Setup

Note: back up any existing configuration files before you overwrite them. The order is meant to serve more as a guide. Some steps are flexibile.

`mv .<TARGET_FILE>-$(date %s).bak`

## Pre-requisites

* [brew](https://brew.sh)
* Unix-like environment

1. `cp .bash_profile $HOME`
2. `cp .bashrc  $HOME`
3. `cp .bash_aliases.git $HOME`
4. `cp .zshrc $HOME`
5. `brew install zsh` 
6. sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" # install [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)
7. Download and install the [MesloLGS NF font family](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)
8. git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
9. `p10k configure`
10. `brew install vim`
11. `brew install tmux`
12. `cp .tmux.conf $HOME`
13. `cp .vimrc $HOME/vim`
14. `cp .gitconfig $HOME`
15. `cp .profile $HOME` # for rbenv
16. `git clone https://github.com/agkozak/zsh-z.git $ZSH_CUSTOM` # download z for zsh
17. source /path/to/zsh-z.plugin.zsh # add to zshrc
18. `brew install the_silver_searcher`



