# Arduino 
This project involves designing and building a custom Arduino board using the ATmega328P microcontroller, the same chip used in the original Arduino Uno. The goal was to understand how the Arduino works at the hardware level and recreate it from scratch.

⚙️ Key Highlights:
Built a standalone Arduino Uno-compatible board using ATmega328P-PU

Designed the circuit with crystal oscillator, capacitors, resistors, and reset button

Burned the bootloader to the ATmega328P using an Arduino as ISP

Uploaded sketches via FTDI module or USB-to-Serial adapter

🧩 Components Used:
ATmega328P microcontroller (DIP package)

16 MHz crystal oscillator

22pF capacitors ×2

10kΩ pull-up resistor for reset

100nF capacitors for power filtering

Optional: LEDs, voltage regulator, FTDI module

🛠️ Objectives:
Learn how Arduino boards work at the hardware level

Practice bootloader burning and programming microcontrollers

Create a cost-effective, minimal version of Arduino Uno
