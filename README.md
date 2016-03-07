Adafruit_LSM303
===============

This is a library for the Adafruit triple-axis accelerometer/magnetometer LSM303DLHC breakout

Designed specifically to work with the Adafruit LSM303 Breakout 
  ----> https://www.adafruit.com/products/1120

These displays use I2C to communicate, 2 pins are required to interface
Adafruit invests time and resources providing this open source code, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Check out the links above for our tutorials and wiring diagrams 

Written by Kevin Townsend for Adafruit Industries.  
BSD license, all text above must be included in any redistribution

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder Adafruit_LSM303. Check that the Adafruit_LSM303 folder contains Adafruit_LSM303.cpp and Adafruit_LSM303.h

Place the Adafruit_LSM303 library folder your *arduinosketchfolder*/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.

<!-- START COMPATIBILITY TABLE -->

## Compatibility

MCU                | Tested Works | Doesn't Work | Not Tested  | Notes
------------------ | :----------: | :----------: | :---------: | -----
Atmega328 @ 16MHz  |      X       |             |            | 
Atmega328 @ 12MHz  |      X       |             |            | 
Atmega32u4 @ 16MHz |      X       |             |            | 
Atmega32u4 @ 8MHz  |      X       |             |            | 
ESP8266            |      X       |             |            | 
Atmega2560 @ 16MHz |      X       |             |            | SDA/SCL D20/D21
ATSAM3X8E          |      X       |             |            | SDA/SCL D20/D21
ATSAM21D           |      X       |             |            | 
ATtiny85 @ 16MHz   |      X       |             |            | 
ATtiny85 @ 8MHz    |      X       |             |            | 
Intel Curie @ 32MHz |      X       |             |            | 

  * ATmega328 @ 16MHz : Arduino UNO, Adafruit Pro Trinket 5V, Adafruit Metro 328, Adafruit Metro Mini
  * ATmega328 @ 12MHz : Adafruit Pro Trinket 3V
  * ATmega32u4 @ 16MHz : Arduino Leonardo, Arduino Micro, Arduino Yun, Teensy 2.0
  * ATmega32u4 @ 8MHz : Adafruit Flora, Bluefruit Micro
  * ESP8266 : Adafruit Huzzah
  * ATmega2560 @ 16MHz : Arduino Mega
  * ATSAM3X8E : Arduino Due
  * ATSAM21D : Arduino Zero, M0 Pro
  * ATtiny85 @ 16MHz : Adafruit Trinket 5V
  * ATtiny85 @ 8MHz : Adafruit Gemma, Arduino Gemma, Adafruit Trinket 3V

<!-- END COMPATIBILITY TABLE -->
