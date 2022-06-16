# Firmware

- github: https://github.com/grbl/grbl
  - get latest release
  - get the hex file
- tools: `brew install avrdude`
- `avrdude -c arduino -P /dev/cu.usbmodem11101 -p atmega328p -U flash:w:/Users/brendenvogt/Downloads/grbl_v1.1h.20190825.hex:i -b 115200`
