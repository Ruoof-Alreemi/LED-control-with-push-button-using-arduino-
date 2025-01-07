# LED-control-with-push-button-using-arduino
## Overview
This project demonstrates how to control an LED using a push button with an Arduino board. When the button is pressed, the LED toggles on and off. This simple circuit can be a great starting point for learning about digital inputs and outputs.

## Components Required
- **Arduino Board** (e.g., Arduino Uno)
- **Push Button**
- **Resistor** (220Ω or 330Ω for the LED)
- **LED** (Light Emitting Diode)
- **Breadboard and Jumper Wires**


## Instructions
1. **Connect the Arduino to your computer** using a USB cable.
2. **Open the Arduino IDE** and copy the code above.
3. **Select the correct board and port** from the Tools menu.
4. **Upload the code** to the Arduino.

## Testing the System
1. **Press the button**: The LED should light up when the button is pressed.
2. **Release the button**: The LED should turn off when the button is released.

## Notes
- Ensure that the resistor used is appropriate to protect the LED from excessive current.
- The `INPUT_PULLUP` mode avoids the need for an external pull-down resistor.
