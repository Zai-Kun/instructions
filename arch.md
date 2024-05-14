1. just install arch however you like
2. chroot into your fresh arch and run:
    1. `sudo pacman -Syu networkmanager network-manager-applet pulseaudio pavucontrol waybar rofi swaybg foot wireguard-tools gnome-keyring`
    2. `cd /tmp && git clone https://aur.archlinux.org/paru-bin.git && cd paru-bin && makepkg -si && paru -S swayfx`
    3. `sudo systemctl enable --now NetworkManager.service && sudo systemctl enable --now systemd-resolved.service`
