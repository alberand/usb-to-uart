# CH330_Hardware

I created this board because I wanted to play with the CH330N because it was supposed to be a crystal-less, <$0.35 USB UART converter in a SOIC-8 package. Since these chips were available from LCSC, I created a quick design and ordered both together.

Since the IC is very small (other USB UART converters are packed in at least a QFN or SOIC-16), I didn't want the board to get much bigger. Accordingly, I developed this 10*10mm USB UART converter board with the CH330N and micro-USB. The assembly is quite fiddly, I suggest that you reflow the USB port and then solder the CH330N (and the LEDs) by hand. If you want to order these boards, I recommend you panelize them.

The CH330N enumerates as CH340 or CH341 and its transfer speed goes up to ~2Mb/s.

[More Info](https://twitter.com/JanHenrikH/status/1057014341155872769)

![Front](https://raw.githubusercontent.com/Jan--Henrik/CH330_Hardware/master/images/front.png)
![Back](https://raw.githubusercontent.com/Jan--Henrik/CH330_Hardware/master/images/back.png)
