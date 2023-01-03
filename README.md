# polus-bash-theme
Polus is a simple bash theme. Please contribute to this repository for a better prompt
# Installation
```
curl -L https://raw.githubusercontent.com/rashed145/polus-bash-theme/main/polus.bash-theme -o ~/.config/bash/themes/polus.bash-theme --create-dirs
echo "source ~/.config/bash/themes/polus.bash-theme"| tee -a ~/.bashrc
```
# Font to use
I recommend Hack Nerd Font for this theme.
You can use any other Nerd Font you like.
But Nerd Font is recommended.

[Download Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts/blob/v2.2.2/patched-fonts/Hack/Regular/complete/Hack%20Regular%20Nerd%20Font%20Complete.ttf?raw=true)

# Install Hack Nerd Font in termux
```
curl -L https://github.com/ryanoasis/nerd-fonts/blob/v2.2.2/patched-fonts/Hack/Regular/complete/Hack%20Regular%20Nerd%20Font%20Complete.ttf?raw=true -o ~/.termux/.fonts/Hack.ttf --create-dirs
ln -sf ~/.termux/{.fonts/Hack.ttf,font.ttf}
termux-reload-settings
```
