## Adafruit CP2102N Friend - USB to Serial Converter PCB

<a href="http://www.adafruit.com/products/5335"><img src="assets/5335.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit CP2102N Friend - USB to Serial Converter. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5335

### Description


Long gone are the days of parallel ports and serial ports. Now the USB port reigns supreme! But USB is hard, and you just want to transfer your every-day serial data from a microcontroller to computer. What now? Enter the Adafruit CP2102N Friend!

The CP2102N is very similar to the CP2104. Despite having a name with a lower number, its actually considered the successor/next generation to the CP2104. Compared to the CP2104, the CP2102N can:

* Transfer data at a faster rate: CP2104 is 2Mbps max, the CP2102N is 3Mbps max
Reprogram the internal settings: CP2104 has a one-time-programmable memory and the CP2102N has reprogrammable settings memory. 99% of people don't use this capability but it is there if you need it.
* The CP2102N improves over the CP2012 (no N) by having the same RS-485 and GPIO support that the CP2104 has
* More details in the SiLabs CP2104 to CP2102N migration guide.
* We've also updated this breakout from our CP2104 Friend so that it has USB C instead of Micro B. It is otherwise 'drop in compatible' and anywhere you would use the CP2104 for uploading firmware to microcontrollers, it'll work exactly the same.

This is a high-quality CP2102N USB-Serial chip that can upload code at a blistering 3Mbit/s for fast development time. It also has auto-reset for Arduino/ATmega328 boards so no noodling with pins and reset button pressings. The CP2102N has better driver support than the CH340 and can do very high speeds, and variable speeds without stability issues. Compared to the FT232RL and FT231X, the CP2102N has the same capabilities or better, at a great price! It even has the RX/TX LEDs to help you debug your data, they'll blink when the chip receives/transmits data.

By default, we've set it up so that it matches our FTDI cables. The 6th pin is RTS, the power wire is +5V and the signal levels are 3.3V (they are 5V compliant, and should work in the vast majority of 3.3V and 5V signal systems). Works excellently with any Arduino, ESP8266, ESP32 or any other microcontroller that uses an 'FTDI port' for communications and upload. You can also purchase a 6-pin extension cable from us, which will let you rearrange the wire order.

There's also a full collection of all the modem control pins you may need on the side, in case you need the DTR, RI, DSR, etc. pins.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
