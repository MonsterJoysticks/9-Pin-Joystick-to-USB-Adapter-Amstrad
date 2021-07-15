# 9 Pin Joystick to USB Adapter
Amstrad joystick and controller focused firmware for the 9 Pin Joystick to USB Adapter https://monsterjoysticks.com/9-pin-joystick-to-usb-adapter

This firmware for the adapter allows you to connect CPC/GX4000 compatible joysticks and controllers to your computer via USB.

The adapter is detected as a USB HID joystick and is compatible with the following;
* Windows
* MacOS
* Most Linux Distros

# Updating the Firmware

Once you have compiled the firmware hex file you can use the BootloadHID <https://www.obdev.at/products/vusb/bootloadhid.html> command line utility to flash the file to the device via USB. 

You will just need to change the position of the small switch on the device so that it is closer to the 9 pin connector and then connect the device to your computer via USB. once connected the bootloadhid software should be able to flash the device, you can then return the switch to it's original position and reconnect the USB cable.
