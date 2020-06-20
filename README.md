# Component Tester OLED

## Installation

## Uploading the .HEX file and .EEP file to MCU

<code>avrdude -c usbasp -B 20  -p m328p -P usb -U flash:w:./TransistorTester.hex:a -U eeprom:w:./TransistorTester.eep:a</code>

## Setting the FUSES

<code>avrdude -c usbasp -B 200  -p m328p -P usb  -U lfuse:w:0xe2:m -U hfuse:w:0xd9:m -U efuse:w:0xfc:m</code>