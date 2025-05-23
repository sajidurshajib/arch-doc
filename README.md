# Arch Linux Installation commands


## Connect Internet

`iwctl` - for enter iwd shell mode
`device list` - check wifi device
`device wlan0 show` - for more information [if your wifi device is waln0]
`station waln0 get-networks` - to see available networks
`station waln0 connect [network name]` - to connect with wifi router for Internet
`exit` - from iwd mode then you can ping


## Update package database 

`pacman -Sy` - synchronize package database
`pacman -Syy` - synchronize core too


## Format drive

`lsblk` - to see connected drive 
`fdisk -l` - to see detail
`gdisk /dev/sda` - to format drive (use command x and z, you can use help command)


## Verify public key

`packman -Sy archlinux-keyring`


## Arch linux Install script

`pacman -Sy archinstall`

## Run archinstall

`archinstall` 


