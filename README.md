# Heater Control Program
<h2>Description</h2>
This repository contains code for controlling a heater using a microcontroller. The code is written in C language and is intended to be used with a PIC 16F877 microcontroller.<br><b>2017</b>
<h2>Setup</h2>
To run this code, you need to have the following components:<br><br>

- PIC 16F877 microcontroller<br>
- Heater<br>
- Temperature sensor<br>
- Computer with a serial port<br>

The temperature sensor should be connected to the analog pin 2 (AN2) of the microcontroller. The heater should be connected to the pin E2 of the microcontroller.
<h2>Usage</h2>
The code reads the temperature from the sensor and sends it to the computer using the serial port. If the temperature is lower than a predefined threshold (temp), the heater is turned on, and if it is higher, the heater is turned off.

To modify the threshold temperature, change the value of the variable "temp" in the code.
<h2>License</h2>

This code is released under the MIT license. See the [LICENSE](LICENSE) file for more information.
