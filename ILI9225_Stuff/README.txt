The library has been adjusted to be compatible with teensy:
- Changed DefaultFonts, by inserting include<stdint>, removing the majority of the header and changing the type of the PROGMEMs to const unsigned chars

Pinout for the teensy LC can be found in the PINOUT File

Video for reference: https://www.youtube.com/watch?v=ykDntvIS1i0

PINOUTS:
Arduino Nano:
LED	-	5V  VCC
CLK	-	13	SCK
SDI	-	11	MOSI
RS	-	9	digital
RST	-	8	digital
CS	-	10	SS

Teensy LC

LED	-	3V3	VCC
CLK	-	13	SCK0
SDI	-	11	MOSI0
RS	-	9	  digital
RST	-	8	  digital
CS	-	10	CS0



