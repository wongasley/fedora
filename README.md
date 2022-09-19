# fedora
# change download speed
```
sudo nano /etc/dnf/dnf.conf
```
#paste this on the dnf.conf file
```
fastestmirror=true
deltarpm=true
max_parallel_downloads=10
```
# update
```
sudo dnf update -y
sudo reboot
```
# repositories
```
sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm
sudo dnf install https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm
```
# flatpak
```
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
# essential apps
```
sudo dnf install gnome-tweaks gnome-extensions-app -y
sudo dnf install vlc -y
sudo dnf install python3 python3-pip -y
sudo dnf install gnome-tweaks gnome-extensions-app -y
flatpak install flathub com.visualstudio.code -y
flatpak install flathub com.discordapp.Discord -y
flatpak install flathub com.spotify.Client -y
flatpak install flathub org.telegram.desktop -y
flatpak install flathub cc.arduino.arduinoide -y
flatpak install flathub com.transmissionbt.Transmission -y
flatpak install flathub com.bitwarden.desktop -y
flatpak install flathub org.gimp.GIMP -y
flatpak install flathub com.obsproject.Studio -y
flatpak install flathub org.shotcut.Shotcut -y
flatpak install flathub org.bitcoincore.bitcoin-qt -y
flatpak install flathub org.godotengine.Godot -y
sudo dnf install akmod-nvidia -y
sudo dnf install xorg-x11-drv-nvidia-cuda -y
```
