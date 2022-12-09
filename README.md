# polus-bash-theme
Polus is a simple bash theme. Please contribute to this repository for a better prompt
# Installation
```
mkdir -p ~/.bash_themes
curl -L https://raw.githubusercontent.com/rashed145/polus-bash-theme/main/polus.bash_theme -o ~/.bash_themes/polus.bash_theme
echo "source ~/.bash_themes/polus.bash_theme"| tee -a ~/.bashrc
```
# Font to use
I recommend FiraCode Nerd Font for this theme.
You can use any other Nerd Font you like.
But Nerd Font is recommended.

[Download FiraCode Nerd Font](https://github.com/ryanoasis/nerd-fonts/blob/v2.2.2/patched-fonts/FiraCode/Medium/complete/Fira%20Code%20Medium%20Nerd%20Font%20Complete.ttf?raw=true)

# Install FiraCode Nerd Font in termux
```
mkdir -p ~/.termux ~/.fonts
curl -L https://github.com/ryanoasis/nerd-fonts/blob/v2.2.2/patched-fonts/FiraCode/Medium/complete/Fira%20Code%20Medium%20Nerd%20Font%20Complete.ttf?raw=true -o ~/.fonts/FiraCode.ttf
ln -sf ~/.fonts/FiraCode.ttf ~/.termux/font.ttf
termux-reload-settings
```
# Screenshot
![Prompt_Screenshot](screenshot.jpg)
