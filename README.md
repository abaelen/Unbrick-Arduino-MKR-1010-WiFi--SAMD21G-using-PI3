# Unbrick Arduino MKR 1010 WiFi (SAMD21G) using PI3
 Load bootloader onto the Arduino MKR 1010 WiFi (SAMD21G) using a raspberry PI3

This Github will describe the different steps to reload a bootloader onto the Arduino MKR Wifi 1010.
Using this reload will make the Arduino MKR WiFi 1010 responsive again, allowing to use the upgrade firmware functionality available from Arduino IDE. Upgrading the firmware using the Arduino IDE ensures full compatibility and integrity towards the latest Arduino standards.

When to use this functionality?
This functionality should only be used in case there is no other option to restore the Board's functionality.
This will exclude all scenarios where the Arduino MKR USB connection is still recognized by the PC.
This will exclude all scnearios where the user has access to a debugger, eg. the ATMEL ICE or the J-LINK

In case one is confronted with a responsive USB connection, but the USB is not enumerated by the computer, the user is adviced to first to multiple tries to activate the bootloader state of the board. This is done by double clicking the reset button on the board.
The user should also exclude the possiblity of a malfunctioning USB driver.

The use of this manual is to the descretion of the user and to its liability only.
(what can happen right? Even not magic smoke...)

That said, let get hacking!

The step-by-step manual can be found on the github page with this readme file.

 Have fun!
