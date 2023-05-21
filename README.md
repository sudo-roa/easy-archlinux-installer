日本語のREADMEは[こちら](./README_JP.md)

# Easy Arch Linux Installer
Scripts for Arch Linux installation
Easy and quick to install Arch Linux

## Requirements
- UEFI boot
- Virtualbox or New PC
- Arch Linux iso image

## Preparation
- ISO image
- Network connection
- Disk partition plan
- Hostname, root password, user name, user password
### ISO image
Download ISO image [here](https://www.archlinux.jp/download/)

### Network
Use `ping archlinux.jp` command to check network connectivity
- on Virtual Box
Maybe it is set up with NAT so you dou't have to do anything

- on PC
    - Wire
      - Nothing special to do if you connect the wires
    - Wireless
      - Use iwd to make wireless connections

## Scripts
### eali-base
### eali-xfce4
### eali-i3

## Usage
If there are no errors in any program, a green "Successfully Installed!!" will appear
### eali-base
1. Clone this repository on archiso
2. Change directory to cloned directory
3. Execution of `chmod +x eali-base` command
4. Execution of `./eali-base` command
5. Reboot and unplug the bootable device
6. Check OS startup

### eali-xfce4 or eali-i3
1. Clone this repository on your Arch Linux
2. Change directory to cloned directory
3. Execution of `chmod +x eali-*` command
4. Execution of `./eali-xfce4 or ./eali-i3` command
5. Reboot and check startup xfce4 or i3

## References
- [archlinux wiki](https://archlinux.org/)
  - [Installation guide - Archwiki](https://wiki.archlinux.org/title/installation_guide)
  - Prtitioning - Archwiki
  - iwd - Archwiki
  - AUR helpers -Archwiki
  - 

## Author
[sudo-roa](https://github.com/sudo-roa)

