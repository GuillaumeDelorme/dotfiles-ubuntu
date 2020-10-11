# Dotfiles and things to do after fresh Ubuntu install

## Update and install usefull apps

```
sudo apt update
sudo apt upgrade
sudo apt install gnome-tweak-tool chrome-gnome-shell zsh git gimp curl inkscape build-essential blender docker
sudo apt clean
sudo snap install beekeeper-studio chromium codium discord intellij-idea-community keepassxc libreoffice slack
```

## Theming

Icons : https://github.com/Jannomag/Yaru-Colors

Gnome extensions to install :
- https://extensions.gnome.org/extension/307/dash-to-dock/
- https://extensions.gnome.org/extension/19/user-themes/

Removing Ubuntu Dock :
```
sudo apt-get purge gnome-shell-extension-ubuntu-dock
```

Ajust dash to dock setting and use gnome-tweak-tools choose icons, theme...

## ZSH

- Install a nerd font : https://github.com/ryanoasis/nerd-fonts (I use "Hack Nerd Font")
- Choose the nerd font in your terminal
- Install oh my zsh : https://ohmyz.sh/
- Install Powerlevel10k : https://github.com/romkatv/powerlevel10k
- Use ~/.p10k.zsh and ~/.zshrc of this repo
