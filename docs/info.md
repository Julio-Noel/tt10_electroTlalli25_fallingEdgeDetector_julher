<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This circuit is used to detect the rising and falling edge conditions when an input button is pressed. The system is clock synchronized; x1 flipflop type D, x2 AND, and 1x NOT are used to determine the system status.

## How to test

Press the button and verify the rising and falling edge LED.

## External hardware

To verify the system, you have to connect a pull-down single-button circuit to the IN0. Furthermore, x2 led circuits have to be connected to the OUT0 and OUT1 for the rising and falling detection, respectively. An Oscilloscope is needed to verify the signals.
