# hello-world

This repo contains some useful shell commands.

## rename a batch of files
`man rename`

Example: `rename -v "s/old_extension/new_extension/" *.old_extension`

## connect to a vpn
`openvpn ovpn_key.ovpn`

## scan network
`nmap -sn 192.168.1.0/24`

## cloning an existing repo from GitHub
`git clone https://github.com/timjzee/repo_name`

## checking connection of usb devices, filesystem, mounting and unmounting
`dmesg`

`fdisk /dev/sdX -l`

`mount /dev/sdX /mnt`

`umount /mnt`

## extract archive
`tar -xzvf <filename>.tar.gz`

## mining protocol
### Check opencl as root
`# clinfo`
### Start xserver in screen
`xinit`
### Run atitweak to overclock gpu
`atitweak --set-engine-clock=650 --performance-level=2 --adapter=0`
`atitweak --set-memory-clock=950 --performance-level=2 --adapter=0`
### Start Marlin in screen
`runMarlin.sh`
### Check temperature with atitweak
`atitweak -s | grep 'temp'`
