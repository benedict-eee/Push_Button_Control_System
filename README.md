# Arduino Push Button Control System
The Push Button Control System is an Arduino-based project that demonstrates how to control one or more LEDs using push buttons.

##Objective
The objective of this project is to understand how to read digital inputs from push buttons,Control LEDs using digital outputs,Implement toggle logic (press once = ON, press again = OFF).

##Components Used
Arduino Uno
LED 
Resistor (220Ω)
Breadboard
Jumper Wires
Push button(s)

##How It Works
The Arduino continuously reads the state of the push button.
When a button press is detected, the program changes the LED state.
Toggle logic ensures that:
First press turns the LED ON
Second press turns the LED OFF
The process repeats with each button press.

##Circuit Diagram
A simple circuit was created using a resistor to limit current flow and protect the LED and so static electricity will not affect the LED from the button.

##Code
The program is written in Embedded C using the Arduino IDE. It uses basic digital I/O functions and push button.

##Results
LED turns ON and OFF at programmed intervals
Correct digital output control achieved

##Skills Gained
Embedded C programming
Arduino IDE usage
Digital electronics basics
Circuit building

##Future Improvements
Control LEDs with long-press detection
Add buzzer or LCD feedback
Expand to relay or motor control
