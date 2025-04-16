# Nextcloud Basics
Guide for people who are looking to setup a basic nextcloud server using ethernet.
The computer that you will setup a server on will be referenced as **target server computer**
Warning, this will erase your disk on the target server computer.

# Prerequisites
- A laptop/computer with decently enough specs
  - Server performance will depend on your specs.
- USB Stick of 8GB or more
- Available computer to flash .iso (different to the target server computer)
- The server will be connected via ethernet, and so will the available computer for this guide.

# Steps
1) Go to https://ubuntu.com/download/server, and download the 24.04 LTS Server .iso file.
2) Open a USB flasher/writer of your choice and flash the iso on to an available USB stick.
3) Boot from the USB on your target server computer, and install Ubuntu Server.
   - When faced with the option to install OpenSSH, select it.
   - Do not mark your boot drive as KVM group.
