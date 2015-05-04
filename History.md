History

## April 26, 2015

 - Boot up, shows rainbow screen. Suspect firmware issue

## April 27, 2015

 - update NOOBS
 - boots up this time; set up Raspberian
 - available on Windows network as 'raspberrypi'
 - possible power supply -- http://shop.pimoroni.com/products/mopi-mobile-pi-power
 - install `samba` to allow access to computer name from Windows machines
 ```
 sudo apt-get update
 sudo apt-get upgrade
 sudo apt-get dist-upgrade
 sudo rpi-update
 sudo reboot
 ```
  - the fourth command updates the raspberry pi firmware
  ```
  arp -a
  ```
   - on windows, lists all computers on the network
   - actaully plug it in right...

   - setup VNC? -- http://elinux.org/RPi_VNC_Server
