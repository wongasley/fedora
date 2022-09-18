# fedora
```
sudo dnf update -y
sudo dnf install gnome-tweaks gnome-extensions-app -y
sudo dnf install vlc -y
sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm -y
sudo dnf install https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm -y
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo -y
sudo dnf install python3 python3-pip -y
sudo dnf install gnome-tweaks gnome-extensions-app -y
flatpak install flathub com.visualstudio.code
flatpak install flathub com.discordapp.Discord
flatpak install flathub com.spotify.Client
flatpak install flathub org.telegram.desktop
flatpak install flathub cc.arduino.arduinoide
flatpak install flathub com.transmissionbt.Transmission
flatpak install flathub com.bitwarden.desktop
flatpak install flathub org.gimp.GIMP
flatpak install flathub com.obsproject.Studio
flatpak install flathub org.shotcut.Shotcut
flatpak install flathub org.bitcoincore.bitcoin-qt
flatpak install flathub org.godotengine.Godot
sudo dnf install akmod-nvidia -y
sudo dnf install xorg-x11-drv-nvidia-cuda
```
