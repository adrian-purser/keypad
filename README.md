# keypad

[Keypad](/images/keypad.png)


## Introduction

A keypad kit for creating custom keypads with up to 54 buttons and/or 3 rotary encoders.  This board was designed primarily for prototyping but is equally suitable for production systems. Two interfaces are available, serial port and/or USB. 

The serial port transmits events (1 byte per event) at 115200 baud. Each event is either a button press, button release or rotary encoder update. The USB interface appears as a standard HID keyboard and doesn't require an extra driver. Either interface can be used to power the board. The serial port requires +3.3V power and supports +3.3V (LVTTL) logic levels.


