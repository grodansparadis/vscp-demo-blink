# vscp-demo-blink

VSCP blink demo is a minimalistic VSCP demo available on multiple platforms. It can be used as a starting point for your own code or as just an example to learn from.

The MDF file for the device is [here](http://eurosource.se/blink01.xml)

The functionality for the demo device is that it blinks a lamp just the same as most blink demos. Some functionality is possible to control.

- It is possible to set the period for the blink between 0-255 seconds, where zero is always off.
- Number of blinks that occurred over time can be read.
- An alarmpoint can be set, where a number of blinks trigger an alarm eventgit.
- Events can be sent when the lamp is turned on and when it is turned off. Which events that should be sent is configurable. 
- Some real and dummy remote variables has been implemented.
