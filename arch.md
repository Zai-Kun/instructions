1. just install arch however you like
2. chroot into your fresh arch and run:
    1. `sudo pacman -Syu base-devel networkmanager network-manager-applet pipewire pavucontrol waybar rofi-wayland swaybg foot wireguard-tools gnome-keyring git resolvconf xorg-xwayland python-pip dunst cliphist github-cli stow sway zsh`
    2. `cd /tmp && git clone https://aur.archlinux.org/paru-bin.git && cd paru-bin && makepkg -si && paru -S wl-clip-persist-git`

3. exit and reboot your system to boot up your arch and run:
    `sudo systemctl enable --now NetworkManager.service && sudo systemctl enable --now systemd-resolved.service`
