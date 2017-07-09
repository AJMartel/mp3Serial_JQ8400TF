# mp3Serial_JQ8400TF
Arduino Library for mp3/wav module based on chinese JQ8400TF chip.

![JQ8400TF module](https://github.com/Cyb3rn0id/mp3Serial_JQ8400TF/blob/master/mp3wav_module.jpg)

This library uses the hardware serial port. 

I've written it for usage with ESP8266 but I've tested it also on Arduino Duemilanove and Arduino Leonardo.

Module that can be used with this library is the one with only 4 pins (vcc, gnd, tx and rx) and micro-sd card.

Library is not suitable for the module with micro-usb port and flash memory on board: this module uses chip JQ8400FL that have different serial commands.

More info on http://www.settorezero.com/wordpress/un-player-wavmp3-economico-controllabile-da-porta-seriale-libreria-per-arduino-e-esp8266/
