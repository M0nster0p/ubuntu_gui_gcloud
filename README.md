# ubuntu_gui_gcloud

Connect to your instance either through SSH option or use gcloud option. Once connected update the source list.

```
sudo apt-get update && sudo apt-get upgrade
```

# Install the Gnome components
Then we need to install the Gnome components for our virtual desktop. So type the following command:
\n choose only one from these 2
1. Full Desktop environment 
```
sudo apt-get install ubuntu-desktop
```
2. Lightweight with core functionality
```
sudo apt-get install gnome-core
```

# Install Google remote desktop and connect to it
open in browser 
```
https://remotedesktop.google.com/headless
```

paste these on console
```
wget https://dl.google.com/linux/direct/chrome-remote-desktop_current_amd64.deb
```
```
sudo dpkg -i chrome-remote-desktop_current_amd64.deb
```
```
rm -rf chrome-remote-desktop_current_amd64.deb
```
```
sudo apt update && sudo apt upgrade
```



