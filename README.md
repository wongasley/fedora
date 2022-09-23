# fedora
# change download speed
```
sudo nano /etc/dnf/dnf.conf
```
# paste this on the dnf.conf file
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
# snapcraft
```
sudo dnf install snapd
sudo ln -s /var/lib/snapd/snap /snap
```
# essential apps
```
sudo dnf install gnome-tweaks gnome-extensions-app vlc python3 python3-pip akmod-nvidia xorg-x11-drv-nvidia-cuda -y
sudo snap install bitwarden
sudo snap install krita
sudo snap install code --classic
sudo snap install gimp
sudo snap install spotify
sudo snap install telegram-desktop
sudo snap install brave
sudo snap install shotcut --classic
sudo snap install obs-studio
sudo snap install blender --classic
sudo snap install qbittorrent-arnatious
sudo snap install shotcut --classic
sudo snap install discord
sudo dnf module install nodejs:16
dnf install kernel-devel
git clone https://github.com/RinCat/RTL88x2BU-Linux-Driver.git
cd RTL88x2BU-Linux-Driver/
make
sudo make install
```
