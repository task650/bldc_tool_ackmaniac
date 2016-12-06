Modded BLDC_Tool by Ackmaniac

A Qt gui to control and debug my custom BLDC controller. A complete description and tutorial about how to use it can be found here: http://vedder.se/2015/01/vesc-open-source-esc/

Quick build instructions for Ubuntu:

sudo apt-get install qtcreator qt-sdk libudev-dev libqt5serialport5-dev

qmake -qt=qt5

make clean && make

Allow for serial access without using sudo: sudo adduser $USER dialout

Restart for access changes to take effect sudo reboot now

Start BLDC-tool from inside of the built repo ./BLDC_Tool

Windows and OS X builds available :

https://bldc-tool.support
