# Quick guidline how to install everything

To install yay:
```sh
git clone https://aur.archlinux.org/yay-git
cd yay-git
makepkg -si
```

Then need to install all required packages with yay:
```sh
yay -Syu
yay -S hyprland kitty thunar wofi waybar colloid-catppucin-gtk-theme-git
```

Then pacman packages
```sh
sudo pacman -Syu
sudo pacman -S hyprpaper fastfetch firefox-developer-edition ttf-jetbrains-mono-nerd nwg-look
```

