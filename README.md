# ESP8266-IR-Remote-Example

This sketch is an example of using an ESP8266 as a IR sender controlled by a webpage.

It uses the [IRremoteESP8266 library by markszabo](https://github.com/markszabo/IRremoteESP8266).

This example is the codes for my devices, in order for it to work for you will need to program in your devices codes. I use the [DumpV2 example](https://github.com/markszabo/IRremoteESP8266/blob/master/examples/IRrecvDumpV2/IRrecvDumpV2.ino) in the IRremoteESP8266 library.

## Hardware

- Wemos D1 Mini
- IR LED
- 2N3904 Transistor
- 330 Ohm resistor
- IR receiver (TL1838) - Needed for reading codes

![alt text](http://i.imgur.com/druTsOU.png "circuit")
