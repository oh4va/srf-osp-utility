
Example output:

```
veijo@kirsikka:~/srf-osp-utility$ ./ospupdfw -t beta -fw 0132 
Downloading the firmware:
  https://x.sharkrf.com/fw-beta/osp/srf-osp-1.1-0132.bin
Opening serial device /dev/ttyACM0

SharkRF openSPOT device information (/dev/ttyACM0):
inf
sercon: inf: SharkRF openSPOT (openspot2)
  SRF-OSP-1.1-433 eu v0131 0A236A54 up 278
  diag 0,0000008a,000000a1,00000058,00000057,00000037,00000088
ready.
 

Do you want to continue (Y/N)?
y
Rebooting SharkRF openSPOT device to bootloader
Waiting the bootloader directory /media/veijo/BOOTLOADER/ to show up
Copying srf-osp-1.1-0132.bin to /media/veijo/BOOTLOADER/
Please, wait a couple of minutes

Please, stand by one more minute, the openSPOT is starting up!
veijo@kirsikka:~/srf-osp-utility$ 
```
