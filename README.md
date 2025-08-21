# Interfacing Single & Multiple LEDs with Arduino

This repository demonstrates how to interface **single and multiple LEDs** with an Arduino Uno.  
We start with blinking one red LED, then extend to controlling three LEDs (red, green, yellow) sequentially.

---

## Components Required
- Arduino Uno
- LEDs (Red, Green, Yellow)
- Resistors (300Ω – 1 kΩ each)
- Breadboard
- Jumper Wires

---

## Single LED Setup
- **Anode (long leg)** → Digital Pin 13 (through a resistor)
- **Cathode (short leg)** → GND

<img width="313" height="300" alt="image" src="https://github.com/user-attachments/assets/4baced60-85bc-4a08-a74f-ac47813f31b9" />


---

## Multiple LEDs Setup
- **Red LED anode** → D10 (through resistor), cathode → GND  
- **Green LED anode** → D11 (through resistor), cathode → GND  
- **Yellow LED anode** → D12 (through resistor), cathode → GND  

<img width="357" height="326" alt="image" src="https://github.com/user-attachments/assets/417cb954-7abd-480a-8f22-25bc984b9475" />


---

## Code
- Multiple LEDs sketch → https://www.tinkercad.com/things/jiw8FyKmQ9O-spectacular-blad-wluff 

