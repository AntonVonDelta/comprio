# comprio
This project provides the tools needed for compressing/decompressing bmp for arduino projects

The bmp must be transformed into an array of bytes. "LCD Assistant" from http://en.radzio.dxp.pl/bitmap_converter/ is a great tool that you can use to convert the bmp's.

The array can then be compressed using the simple algorithm posted here. A working version can be found at this link:https://jsfiddle.net/sergiureznicencu/cfLrdufn/ .

On the arduino side, the provided function must be used for decompressing the array and printing it onto the display. This mechanism can be used when memory is very small but processing time is not.
