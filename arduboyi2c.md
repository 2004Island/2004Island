---
layout: default
---
[back](./)

## Arduboy I2C Console

### First prototype was created around August of 2020

This design is based on a schematic for an I2C arduboy that I found on somebody's github. The only reason that I picked designing an I2C arduboy over the SPI version is because I don't have any SPI OLEDs. The I2C version of the arduboy is dependent on the arduboy2 library. The games that I've tested with it are ardu-breakout, micro tanks, flappy ball, and Conway's Game of life. The following image is of the arduboy with the fireplace animation demo.

![Branching](https://i.imgur.com/vg9adDo.jpg)

I designed the PCB in EasyEDA with 2 layers.

![Branching](https://i.imgur.com/Sof5A2v.png)

This is the schematic of the arduboy console with I2C that I used to create this clone. It is a very simple schematic. In theory you can use a joystick for the up down left and right inputs. I did not include the LEDs because it's not necessary for the console to function.

![Branching](https://i.imgur.com/CBg05B9.png)

For battery power, I used a Wemos D1 Mini battery shield. I connected the lipo to the shield's input, and I put a switch between the 5V out and the VIN on the arduino nano. 

![Branching](https://i.imgur.com/3lQ4T4Y.jpg)

### Contact

Email me at varunsreedharan2@gmail.com 
