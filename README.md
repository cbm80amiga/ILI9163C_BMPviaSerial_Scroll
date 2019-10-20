# ILI9163C_BMPviaSerial_Scroll
Photo slideshow via serial interface on Arduino and ILI9163C 128x128 LCD

YouTube video:
https://youtu.be/P4cwA9jNsfQ


Enhanced version of the project from the video:
https://youtu.be/vQY5ILjSZBc

## Purpose
To check LCD features (colors reproduction, brightness, contrast) and you need it quick without playing with SD card modules, libraries, etc.
Project code can be easily modified for any LCD, the only required function is drawPixel()

## Features and How to use
- Added ILI9163C smooth scrolling during picture transfer
- Implemented full BMP structure parsing and support for 8 and 4-bit palette modes
- Convert photos to 128x128 24, 8 or 4-bit Windows Bitmap (use Irfanview)
- Start CoolTerm and set 115200bps serial port speed
- Use "Send TextFile" to send photos to Arduino
- At 128x128 resolution photos transfer in 6s at 24-bit, 2s at 8-bit and 1s at 4-bit
