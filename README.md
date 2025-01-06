Name: Samala Shravya
Company: CodTech IT Solutions Pvt. Ltd
Intern ID: CT12EFC
Domain: Embedded Systems
Duration: December 17, 2024, to February 17, 2025

Project Overview
Project Title: Design a Bluetooth-Controlled Home Automation System to Switch Devices On and Off

Objective
To design a home automation system using Bluetooth technology to control electrical appliances remotely using a smartphone. The system will allow users to switch devices on and off via Bluetooth commands.

Components Required
Arduino Uno/Nano: Microcontroller for system control.
Bluetooth Module: HC-05 or HC-06 for wireless communication.
4-Channel Relay Module: To control multiple devices.
Smartphone: With a Bluetooth terminal app.
Electrical Appliances: e.g., LED, fan.
Breadboard and Jumper Wires: For connecting the components.

Circuit Connections
1. Bluetooth Module (HC-05)
VCC → 5V (Arduino)
GND → GND (Arduino)
TX → RX (Arduino)
RX → TX (Arduino)
2. Relay Module
IN1 → Pin 8 (Arduino)
IN2 → Pin 9 (Arduino)
IN3 → Pin 10 (Arduino)
IN4 → Pin 11 (Arduino)
VCC → 5V (Arduino)
GND → GND (Arduino)
3. Appliances
Connect each appliance’s positive terminal to the relay’s NO (Normally Open) terminal.
Connect the COM (Common) terminal of each relay to the power source.
4. Power Supply
Ensure that the relays can handle the voltage and current requirements of the connected devices.
For safety, use a separate power supply for high-voltage appliances.

How It Works
Bluetooth Pairing: Pair the HC-05 module with your smartphone. The default PIN is either 1234 or 0000.
Control via Bluetooth: Open a Bluetooth terminal app on your smartphone.
Commands: Send the following commands to control the devices:
1: Turn ON Device 1
2: Turn OFF Device 1
3: Turn ON Device 2
4: Turn OFF Device 2
5-8: Control Device 3 and Device 4 similarly

![task 2](https://github.com/user-attachments/assets/b232c17e-aecc-42b4-a872-8bbe02065a1e)
