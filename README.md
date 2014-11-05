Tiny328
=======

This board is derived from the original Tiny328 project started by [Nathan Chantrell](http://nathan.chantrell.net/20130923/tiny328-mini-wireless-arduino-clone/). It has the following design goals:
- Software compatible with Arduino and JeeNode
- Includes an RFM12B radio module from HopeRF
- Easily mountable

Retaining the same form factor as the original Tiny328, I made the following changes:

- Redid the board in Kicad instead of Eagle
- Added two mounting holes
- Split up 3V3 and 5V power input headers
- Made the connection of RFM12B's DSSI pin to D4 optional by solder jumper
- Added footprints for an R1/R2 voltage divider from VCC into A0, so battery voltage
  can be reliably measured against a calibrated atmega 1.1V band gap reference.
   
