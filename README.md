# HP Anywhere PCoIP Client for Arch Linux
Unofficial HP Anywhere PCoIP client package and setup for Arch Linux.

This repo provides an Arch Linux PKGBUILD and optional binary release for the HP Anyware PCoIP Client (25.06.1).

*This is forked from https://github.com/ppira/pcoip-client and updated to work with the latest (25.06.01+) HP Anyware PCoIP Client
*Additionaly added some fixes mentioned in comments the outdated https://aur.archlinux.org/packages/pcoip-client

## Installation

### Option 1: Build from source

git clone https://github.com/shataf-alriq/HP-Anywhere-PCoIP-Client.git 

cd HP-Anywhere-PCoIP-Client

makepkg -si

### Option 2: Download and install binary

wget https://github.com/shataf-alriq/HP-Anywhere-PCoIP-Client/releases/download/v25.06.1-2/pcoip-client-25.06.1-2-x86_64.pkg.tar.zst

sudo pacman -U pcoip-client-25.06.1-2-x86_64.pkg.tar.zst
