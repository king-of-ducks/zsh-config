# Hello
This is my `zsh` config. Feel free to use it, copy and modify as you want
<br>

# Installation (Unix)
Clone this repository to your home directory:
```bash
git clone https://github.com/king-of-ducks/zsh-config.git ~/
```
<br>

Move config itself to home directory and remove previously cloned folder:
```bash
mv ~/zsh-config/.zshrc ~/.zshrc
rm -rf ~/zsh-config
```
<br>

To make it work correctly, install necessary plugins:
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
