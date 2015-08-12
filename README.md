# RaspiLcd
My personal 16x2 LCD messageboard. Used in my RetroPi setup. The pinout may differ from the pinout form the Adafruit examples.

The code is based on the https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code/tree/master/Adafruit_CharLCD repository.

The greatest inprovement I made is to get rid of the endless loop. The board script can be dispatched by an  external call, like a cronjob or by a messagequeue.
