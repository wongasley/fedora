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

```
