1. just install arch however you like
2. chroot into your fresh arch and run:
    -- sudo pacman -Syu networkmanager network-manager-applet pulseaudio pavucontrol waybar rofi swaybg foot wireguard-tools
    -- cd /tmp && git clone https://aur.archlinux.org/paru-bin.git && cd paru-bin && makepkg -si && paru -S swayfx
    -- sudo systemctl enable --now NetworkManager.service && sudo systemctl enable --now systemd-resolved.service
