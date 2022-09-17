# BuddEE
An Arduino-based digital multimeter, waveform generator and oscilloscope.

CONSTRUCTION
Instructions on the construction of the BuddEE platform are detailed in the documentation document.

NOTE: Both the Arduino Mega and the Arduino Mega Pro are usable in the construction of the circuit.

USE
Uncomment the function corresponding to the task you wish the circuit to perform.

Multimeter:
Each measuring sub-circuit has a pair of pins that you are supposed to plug the measured device into. Alternatively,
as also seen in the pictures on the documentation, if the circuit is being used in a breadboard configuration, be sure
the measured ddevice is connected to the correct sub-circuit pins.

Waveform Generator:
1. Write the shape variable to the value corresponding to the desired shape.
    0 = Pulse
    1 = Triangle
    2 = Saw
    3 = Sine
2. Adjust the PWM and Frequency knobs as needed.

Oscilloscope:
1. Plug in the measured device to the oscilloscope pins.
2. Open the Serial Monitor or Serial Plotter to read the measured signal.

NOTE: The instructions on how to use BuddEE are more detailed in the documentation document.
NOTE: If you change a pin for reading signals or decide to use a different-valued resistor, be sure to update the code in the corresponding sub-circuit.
