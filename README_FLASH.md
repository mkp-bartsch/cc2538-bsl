
https://vandalen.dev/post/how-to-update-sonoff-zigbee-3-0-zbdongle-p-usb-firmware-using-a-mac/

brew install wget

ls /dev/tty* | grep usb

python cc2538-bsl/cc2538-bsl.py -ewv -p /dev/tty.usbserial-10 --bootloader-sonoff-usb ./cc2538-bsl/CC1352P2_CC2652P_launchpad_coordinator_20230507.hex