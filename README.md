# sali
Simple Arch Linux Installer

A script managing the installation of Arch Linux with the minimum of user's interaction
and a nice selection of packages (i3 and XFCE are proposed by default).

Requirements:

- Internet connection (obviously)
- GPT partition table with:
  - EFI system partition (100 MB should be enough)
  - Swap partition (optional)
  - Linux filesystem partition
- UEFI-compliant computer with 64-bits CPU

How to run the installer:

1. Boot on your Arch ISO live session
2. Connect to Internet (e.g. with `wifi-menu`)
3. Get the script (e.g. with `wget https://github.com/kilbith/sali/archive/master.zip && unzip *.zip`)
4. Run the script with `./sali`
