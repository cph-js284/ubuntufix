# ubuntufix

```
sudo add-apt-repository "deb http://archive.ubuntu.com/ubuntu $(lsb_release -sc) universe"

sudo apt-get purge --auto-remove gdm3
sudo apt-get purge --auto-remove gnome-shell
sudo apt-get purge --auto-remove gnome-software
sudo apt-get purge --auto-remove lightdm
sudo apt-get purge --auto-remove gnome-session-bin 
sudo apt-get purge --auto-remove gnome-session-common 
sudo apt-get purge --auto-remove ubuntu-session
sudo apt-get purge --auto-remove ubuntu-desktop

sudo apt-get update
sudo apt-get upgrade 
sudo apt-get install ubuntu-desktop
```
