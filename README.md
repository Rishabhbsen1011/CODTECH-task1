Name-Rishabh sen 
 
 company:CODTECH IT SOLUTIONS

ID:CT08DS258

Domain:embedded system

duration:december to january

mentor Neela santhosh kumar

The project demonstrates a simple Arduino-based LED blinking circuit using the ATmega microcontroller. Here’s an overview of the functionality:

![Screenshot 2024-12-21 215445](https://github.com/user-attachments/assets/021e7c6f-3c69-4e7a-84a0-3eacad9daf9d)


**Project Objective:**
The goal of this project is to alternately blink two LEDs connected to pins 6 and 7 of the Arduino board, with each LED staying on for 1.5 seconds (1500 milliseconds) before switching.

**Key Components:**
Arduino Board: Equipped with an ATmega microcontroller for programming and controlling the LEDs.

LEDs: Two LEDs are used, connected to pins 6 and 7 of the Arduino board.

Resistors: Optional, to limit current to the LEDs and prevent damage.

Wiring: Ensures proper connections between the LEDs, resistors, and Arduino pins.

Code Breakdown:

void setup():

Initializes the pins where the LEDs are connected.

pinMode(6, OUTPUT) sets pin 6 as an output.

pinMode(7, OUTPUT) sets pin 7 as an output.

void loop():

Creates a continuous loop to alternate the state of the LEDs.

The following sequence occurs repeatedly:

Pin 6 is set to HIGH (LED on), and pin 7 is set to LOW (LED off).

A delay of 1.5 seconds (1500 milliseconds) is introduced.

Pin 6 is set to LOW (LED off), and pin 7 is set to HIGH (LED on).

Another 1.5-second delay is introduced.

Working Principle:

The program uses digitalWrite() to control the voltage levels on pins 6 and 7, turning the LEDs on or off.

The delay(1500) function pauses the execution for 1.5 seconds between each state change, creating the blinking effect.

Application:

This project serves as a beginner-friendly example to:

Learn basic Arduino programming.

Understand how to control output pins.

Work with simple electronic circuits involving LEDs.

Possible Improvements:

Dynamic Timing: Use a potentiometer or buttons to adjust the blinking interval.

Additional LEDs: Extend the project by adding more LEDs or creating more complex patterns.

Energy Efficiency: Optimize the delay mechanism by incorporating a low-power mode or using interrupts.
