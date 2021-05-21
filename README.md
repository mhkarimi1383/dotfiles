# dotfiles
My dot file for configurations are here

## For vim I'm using spaceVIM (I'm lazy)
to install it run the command below
```bash
curl -sLf https://spacevim.org/install.sh | bash
```
## For tmux I'm using [this repo](https://github.com/gpakosz/.tmux) (I'm lazy Again)

## to make zsh working you should do the steps below (Of course you need OH my zsh)
1. install power10k
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
2. clone custom thing that are added
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## Note: You should change home directory location in `.zshrc` and `.bashrc`
