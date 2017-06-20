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
