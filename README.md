
# install-Microsoft-Edge-23-06-24

New_repository_for_libu2f-udev

Add this line in src.list:

sudo nano /etc/apt/sources.list

deb http://deb.debian.org/debian buster main


sudo apt update
sudo apt install libu2f-udev


Remove the Debian repository Buster after installation:
sudo nano /etc/apt/sources.list

remove this line :
deb http://deb.debian.org/debian buster main
