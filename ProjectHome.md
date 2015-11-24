Accelerometer\_Mouse

> This code reads the Memsic 2125 two-axis accelerometer, converts the pulses
> output by the 2125 into milli-g's (1/1000 of earth's gravity) and prints
> a mapped version of them over the serial connection to the computer.output.
> It then takes these mapped values and uses them for virtual mouse movement,
> clicking, and scrolling.

> The circuit:
  * X output of accelerometer to digital pin 2
  * Y output of accelerometer to digital pin 3
  * +V of accelerometer to +5V
  * GND of accelerometer to ground

> created by David Kerns of
> The Athenian School on
> Dec 3 2012, with a large
> portion of code taken from
> David A. Mellis' and Tom Igoe's
> found here:
> http://www.arduino.cc/en/Tutorial/Memsic2125