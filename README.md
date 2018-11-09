# MINISFORUM
Steps to install your preferred Linux distrib on MinisForum PC
See https://www.amazon.fr/Ventilateur-MINISFORUM-Processeur-Graphiques-Sortie-HDMIetVGA/dp/B07F9VZ3XK

##
* Prepare a usb stick with your preferred Linux distribution image 
* MAC : 
* run "diskutil list" to get the identifier, eg disk1s1
* sudo diskutil umount /dev/disk1s1
* sudo dd if=Downloads/ubuntu-16.04.5-server-amd64.iso of=/dev/disk1s1 bs=1m
* 
*
* Plug your MinisForum PC (power, keyboard, mouse, network, screen)
* !! Plug you usb disk containing the Linux image    
* Switch on the MinisForum PC
* Press Suppr to enter the BIOS
* In the main tab of the BIOS, set time and date
* In the Boot tab of the BIOS, set Boot Option #1 to USB Key
* In the Boot tab of the BIOS, set Boot Option #2 To #8 to disabled
* In the Boot tab of the BIOS, set UEFI Hard DiskDrive BBS priorities, Boot Option #1 to Disable
* In the Boot tab of the BIOS, set UEFI USB Key Drive BBS Priorities Boot Option #1 your usb stick model brand 
* In the tab Save & Exit, select Saves Changes and Exit

* When rebooting, MinisForum PC will boot on the usb stick
* Install Linux
** Select your preferred language
** Select your keyboard
** ...
* When instructing to reboot and before to reboot remove the USB stick
* Reboot
* Pres Suppr to enter the BIOS
* Go to the "Boot" tab of the BIOS, select "Boot option #1 to Hard Disk:ubuntu"
* Go to the the tab "Save & Exit", select "Saves Changes and Exit"
* Be happy, it's finished
