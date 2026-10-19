# IoT Smart Lighting System

An embedded systems prototype that automatically toggles a light source based on ambient room brightness. Built and simulated using Arduino and Tinkercad Circuits.

## 📌 Project Overview
This project demonstrates the fundamental logic used in energy-efficient smart home ecosystems and automated municipal streetlights. It utilizes a microcontroller to process analog sensor data and automate physical environments.

## 🛠️ Hardware & Components
* Arduino Uno R3
* LDR (Photoresistor)
* 10kΩ Resistor (for the LDR Voltage Divider)
* LED
* 220Ω Resistor (Current-limiting for the LED)

## 💡 How it Works
The LDR continuously monitors surrounding light levels. As the environment gets darker, the LDR's resistance increases, dropping the voltage read by the Arduino's analog pin (A0). The microcontroller constantly evaluates this incoming data against a calibrated threshold. Once the light level dips into "darkness," the system triggers a digital output (Pin 13) to instantly turn on the LED.

## 📸 Circuit Diagram
*(Ensure you uploaded the image as Circuit_Diagram.png for this to show up)*
![Circuit Diagram](Circuit_Diagram.png)

## 💻 Code
The logic is written in C++ and uses standard Arduino libraries for ADC (Analog-to-Digital Conversion) and digital output. 

Check the `Smart_Light.ino` file for the complete source code.
