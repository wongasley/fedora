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
```
