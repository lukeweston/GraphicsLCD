
Breakout board or interface board for LCD displays.

Intended mainly for KS0108-compatible graphical LCD displays or similar. (Usually 128 x 64 pixels.)

This board allows you to connect a LCD display of this sort to your host microcontroller using a minimal number of pins - and also offloading the processing and memory usage
associated with driving the display away from the host microcontroller and onto the display microcontroller. Based on the Atmel ATmega32U4 (Arduino Leonardo-compatible)
microcontroller.

Serial data is supplied to the microcontroller over either the USB, TTL-level UART, SPI or I2C interfaces - whatever you want. 5V power must also be supplied from the host
microcontroller.
