# Very-Simple-USB-Relay
A Python 3.x module for getting/setting the state of USB Relays. 
![Image of USB Relay](asset.jpg?raw=true)
Specifically, these relays are purchased usually from EBay and come from a Chinese manufacturer. They have Songle relays, or look alikes (ex: CNTENGFEI).

These relays use the USB-HID specification (Human interface device) for communication. 

Upgraded to list and handle multiple relays with the same USB identifiers but different ID's inspired by the enum function from this project:
https://github.com/pavel-a/usb-relay-hid

Tested only on Ubuntu Linux!

# Dependencies
This module depends on the [hidapi module](https://github.com/trezor/cython-hidapi), which can be installed with the following:

    sudo apt-get install python3-dev
    sudo pip3 install hidapi

