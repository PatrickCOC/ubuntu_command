# ubuntu 22.0 wayland(remote desktop)
enable/disable wayland on Ubuntu 22.04 Desktop

* ```sudo nano /etc/gdm3/custom.conf```
* WaylandEnable=true -> WaylandEnable=false
* ```sudo systemctl restart gdm3```
* To login to Ubuntu 22.04 using the Wayland click on the gear button and select Ubuntu option before you login. If you have disabled the Wayland display server, you will only see the Xorg option appear, or the gear button doesn’t show up at all.
# ubuntu_command
# ubuntu_command
