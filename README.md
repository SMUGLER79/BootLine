# BootLine
Engineering a fully bootable Linux OS from scratch, compiling 80+ packages across 300+ build steps, configuring 20+ system scripts and services, achieving a minimal 4.4 GB footprint, full bash shell environment, on x86-64 systems. 

(This is not a traditional installation. Every component is isntalled from source code, manually configured system settings, and ultimately created a bootable Linux system built by me.)


## Version and Build Plan
**Target System**: x86_64 Pure 64-bit </br>
**Partitioning**: Manual fdisk + formatted with ext4 </br>
**Kernel Version**: Linux 6.13.4 </br>
**Bootloader**: GRUB 2.12 </br>
**Shell**: Bash 5.2.37 </br>

## Packages Used
Here is a list of all the packages that I have used along with their versions: [Here.](https://github.com/SMUGLER79/BootLine/tree/main/All%20Packages)
