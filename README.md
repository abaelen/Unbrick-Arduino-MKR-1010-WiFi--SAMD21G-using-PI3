# Unbrick Arduino MKR 1010 WiFi (SAMD21G) using PI3
 Load bootloader onto the Arduino MKR 1010 WiFi (SAMD21G) using a raspberry PI3

This Github will describe different tips & tricks to reload a bootloader onto the Arduino MKR Wifi 1010.
Using this reload will make the Arduino MKR WiFi 1010 responsive again, allowing to use the upgrade firmware functionality available from Arduino IDE. Upgrading the firmware using the Arduino IDE ensures full compatibility and integrity towards the latest Arduino standards.

When to use this functionality?
This functionality should only be used in case there is no other option to restore the Board's functionality.
This will exclude all scenarios where the Arduino MKR USB connection is still recognized by the PC.
This will exclude all scnearios where the user has access to a debugger, eg. the ATMEL ICE or the J-LINK

In case one is confronted with a responsive USB connection, but the USB is not enumerated by the computer, the user is adviced to first try multiple times to activate the 'bootloader state'. This is done by tapping twice the reset button on the board.
The user should also exclude the possiblity of a malfunctioning USB driver.

The use of these tricks are to the descretion of the user and to its liability only.
(what can happen right? Even not magic smoke...)

That said, let's get hacking!

The tips & tricks weigh heavily on the work of Lady Ada, 'programming microcontrollers using openocd on raspberry pi'. 
95% of the steps are found in this manual, published on webpage, you-tube as well as pdf, found here:
https://learn.adafruit.com/programming-microcontrollers-using-openocd-on-raspberry-pi
--> a big thanks for the support adafruit is providing to the community of makers! So be adviced to check their pages frequently for their valuable updates, support & learnings.


What is this Github useful for?
 Well, providing the last 5% of tips, I was missing to get it 100% working. Provided a night spend, I wanted to share these little tips.

The step-by-step with tips & tricks can be found on the github page with this readme file.

Advance by opening the 'Manual Tips & Tricks' in this Github

 Have fun!
