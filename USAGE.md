# How to Use This ArcoLinux Preservation Repo

## 1. Add to pacman.conf

Edit `/etc/pacman.conf` (as root) and add this section at the bottom:

```ini
[arcolinux-preservation]
SigLevel = Optional TrustAll
Server = https://TabooTrader.github.io/arcolinux-preservation/$arch
Server = https://raw.githubusercontent.com/TabooTrader/arcolinux-preservation/main/$arch
