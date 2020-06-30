# JevilOS - An OS that can do anything
## A guide to fan-based builds:

Install as many of these packages as possible:
+ Wine
+ Darling
+ DOSBOX
+ FireFox
+ RetroArch
+ VirtualBox
+ APT+dpkg
+ Snaps
+ Firefox
+ XFCE4 base with WIFI, PulseAudio, Terminal, Mousepad, and Thunar File Manager
+ Essential packages for making a QEMU VM via script
- Everything else.


So essentially you can install these as accurately as possible, according to your architecture and OS:
* Install Ubuntu Server or equivilent with credentials:
	* Full Name: JevilOS User
	* Build username: jevilos
	* Build password: password

* Once installed, start with: sudo dpkg --add-architecture i386
	* (For x86_64/amd64 only)

* sudo apt update

* sudo apt install -y retroarch wine-stable dosbox virtualbox virtualbox—ext–pack xfce4 \
xfce4-pulseaudio-plugin xfce4-power-manager network-manager-gnome \
mousepad thunar xfce4-terminal lightdm

* sudo apt-get install qemu-system qemu-utils python3 python3-pip

* sudo apt install -y open-vm-tools

* sudo apt install -y firefox

* Reboot, install darling dependencies, and follow directions at: https://github.com/darlinghq/darling/releases to install the latest release
	*  (For x86_64/amd64 only)

* Clear all FireFox data.

* git lcone  https://github.com/Distroshare/distroshare-ubuntu-imager

* Use distroshare-ubuntu-imager or equivalent to setup live CD.