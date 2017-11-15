# Dotfiles
These dotfiles are managed using 
[GNU Stow](https://www.gnu.org/software/stow/stow.html).

## Installation
Clone and install:

```shell
$ git clone https://github.com/robbert-vdh/dotfiles.git ~/.dotfiles
$ cd ~/.dotfiles
$ ./install.sh
```

## Spacemacs layers
I've got Spacemacs layers for the following packages:

-   irony-mode (faster C/C++ auto completion)
-   languagetool (grammar correction)
-   platformio (embedded system development)

They can be found over
at [user/emacs/.emacs.d/private/layers](user/emacs/.emacs.d/private/layers),
along with installation instructions.

## xfce + i3
KDE handles most non-WM shortcuts and things like text rendering and themes.

-   Arc GTK theme
-   arc-kde
-   compton
-   feh
-   i3-gaps-next-git
-   konsole
-   kvantum
-   Liberation Mono font
-   light-locker
-   qt5ct
-   Papirus icon theme
-   playerctl for Spotify
-   Roboto font
-   xdotool
-   xfce4
-   xfce4-notifyd (should be started as a systemd user service)
-   xfce4-i3-workspaces-plugin-git

### Screenshots
-   imgurbash2
-   maim
-   slop

### Autostarted
-   albert
-   kdeconnect
-   keepassxc
-   network-manager-applet
-   redshift
