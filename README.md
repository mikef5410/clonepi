
Clone a raspberry pi with Arch Linux on it.

1. power down the pi, move the micro-sd to a machine with these scripts
2. ./cloneDisk /dev/mmcblk0
3. put a new micro-sd in the machine
4. ./MakeSD /dev/mmcblk0 newHostname

Boot from the new disk and test it out.

