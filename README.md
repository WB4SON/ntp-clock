ntp-clock
=========

This clock is designed to run on a Raspberry Pi, and uses an Adafruit 2x16 LCD to display both local
and UTC date/time info.  The LCD is attached to the Raspberry Pi using a LCD Pi Plate, and uses I2C to
control the display.  The LCD Pi Plate push buttons are not currently used

The code can be run as a background task ("&") on startup by making the appropriate /etc/init.d/ script file

