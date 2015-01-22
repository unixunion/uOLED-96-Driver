## uOLED Driver

This uOLED driver is for 4D Systems uOled series of displays.

## About

Based off snipped from here and there.

## Connections

	uOLED tx <----> Arduino rx (d0)
	uOLED rx <----> Arduino tx (d1)
	uOLED gnd <---> GND
	uOLED 5v <----> 5V
	uOLED rst <---> (d8)

## Changelog

* changed to new arduino serial.write(byte) behaviour
* fixed serial.print being used instead of serial.write
* initial import
