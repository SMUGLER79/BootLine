# BootLine
Engineering a fully bootable Linux OS from scratch, compiling 80+ packages across 300+ build steps, configuring 20+ system scripts and services, achieving a minimal 4.4 GB footprint, full bash shell environment, on x86-64 systems. (This is not a traditional installation. Every component is isntalled from source code, manually configured system settings, and ultimately created a bootable Linux system built by me.)

## ⚙️ Version and Build Plan
**Target System**: x86_64 Pure 64-bit
**Partitioning**: Manual fdisk + formatted with ext4
**Kernel Version**: Linux 6.13.4
**Bootloader**: GRUB 2.12
**Shell**: Bash 5.2.37
