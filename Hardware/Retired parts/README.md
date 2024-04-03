# Some stuff that's no longer needed, but kept around for reference

## old Hardware.tar.gz
Mostly the original project from a couple years ago...

## Control - *.tar.gz
Some expieriments aimed (initially) at looking for a way to enable/disable outputs using I2C control.

At this point, I'm leaning heavily on using Adafruits Seesaw framework with either an [ATTiny](https://learn.adafruit.com/adafruit-attiny817-seesaw) or an [Atmel SAM-D09](https://learn.adafruit.com/adafruit-seesaw-atsamd09-breakout)

* Control - ATSAMD09
  - I2C via Atmel SAM-D09
* Control - ATTinyXX14
  - I2C via 14 pin ATTiny MCU
* Control - ATTinyXX17
  - I2C via 24 pin ATTiny MCU
  - The Big Monster
  - Lotsa flash space
  - Great gobs of GPIO signals
  - This one might have sufficient power to add on a CH340 & a USB-C connector to make a module to control the rest of the modules...
  - Maybe a standalone UPDI programmer to configure new modules prior to isertion.  Have it scan the I2C bus & pick out a free address, then automagically set the new module.

While the ATTiny designs show the 1614 & 1617, Any chip in the family ending with either 14 or 17 respectively should drop right on. (2xx, 4xx,8xx, 16xx, 32xx ... how much flash do ya want?)

Real neat trick...  Apparently, the ATTinyXX27 chips should drop into the ATTinyXX17 footprint & work too!

