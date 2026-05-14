# password-based-door-open-system
A password-based door locking and unlocking system using the LPC2148 microcontroller, keypad, LCD display, DC motor, and motor driver for secure electronic access control.

Project Overview:
This project implements a secure password-based door access system using the LPC2148 ARM7 microcontroller. Users enter a password through a keypad, and the system verifies it. If the password is correct, the DC motor opens the door; otherwise, access is denied.

Features:
Password protected door access
LCD display for user interaction
Keypad-based password entry
DC motor controlled door mechanism
Automatic door open and close operation
Secure electronic locking system

Components Used:
LPC2148 Development Board
LCD Module (16x2)
4x3 Keypad
DC Motor
L293D Motor Driver
Power Supply
Connecting Wires

Software Used:
Keil uVision IDE
Embedded C Programming
Proteus (optional for simulation)

Working Principle:
User enters password using keypad.
LPC2148 reads the entered password.
LCD displays system messages.
If password is correct:
Motor rotates forward.
Door opens.
After delay, motor reverses.
Door closes.
If password is incorrect:
LCD displays “Wrong Password”.


Block Diagram:
<img width="492" height="291" alt="Image" src="https://github.com/user-attachments/assets/155c1db1-28ce-4991-b5b6-ed43755ec35b" />



Circuit Implementation:
<img width="870" height="681" alt="Image" src="https://github.com/user-attachments/assets/7b4267d3-95ed-493c-9dd7-901ff5acd3a0" />

Circuit Connections:
LCD Connections
LCD Pin	LPC2148 Pin
RS	P0.2
EN	P0.3
D4-D7	P0.4 - P0.7
RW	GND

Keypad Connections:
Keypad Pin	LPC2148 Pin
R1	P1.16
R2	P1.17
R3	P1.18
R4	P1.19
C1	P1.20
C2	P1.21
C3	P1.22

Motor Driver Connections:
L293D Pin	LPC2148 Pin
Input1	P0.16
Input2	P0.17
Enable	P0.18

Project Structure:
password-based-door-open-system/
│
├── code/
│   └── main.c
│
├── images/
│   ├── block_diagram.png
│   └── circuit_diagram.png
│
├── report/
│   └── project_report.pdf
│
└── README.md

Applications:
Smart home security
Office access systems
Seminar halls
Conference rooms
College laboratories

Advantages:
Eliminates need for physical keys
Improved security
Easy password authentication
Low-cost embedded security solution

Limitations:
Uses only keypad authentication
No biometric verification
Password can be guessed if weak

Authors
Bobbireddi Pranathi

