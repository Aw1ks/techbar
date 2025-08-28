# Techbar
A techno-themed Waybar[https://github.com/Alexays/Waybar] designed for Hyprland. ## How to install 

## How to install
1. Clone the repository:
```
git clone https://github.com/Aw1ks/techbar.git cd techbar
```
2. Establish dependencies:
- Arch Linux:
```
sudo pacman -S waybar gtk4 json-c cairo pango libxembed networkmanager pulseaudio upower hyprland hyprctl
```
- Ubuntu/Debian:
```
sudo apt update
sudo apt install waybar gtk-4.0 libjson-c5 libjson-c-dev libcairo2-dev libpango1.0-dev libxembed-dev network-manager pulseaudio upower hyprland
sudo apt install pavucontrol # Для on-click действия pulseaudio control
```
- Fedora:
```
sudo dnf install waybar gtk4 json-c cairo pango libXembed-devel NetworkManager pulseaudio upower hyprland
sudo dnf install pavucontrol # Для on-click действия pulseaudio control
```
- openSUSE:
```
sudo zypper install waybar gtk4 json-c cairo pango libXembed-devel NetworkManager pulseaudio upower hyprland
sudo zypper install pavucontrol # Для on-click действия pulseaudio control
```
3. Copy configuration files:
```
mkdir -p ~/.config/waybar/
cp config style.css ~/.config/waybar/
```
4. Restart Waybar to apply the changes:
```
killall waybar
nohup waybar >/dev/null 2>&1 &
```
If errors occur, run the 'waybar' command first - will print all errors when starting waybar.
