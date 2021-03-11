# Microcontroller Based Voltage Stabilizer
Voltage stabilizers are nowadays one of the most important requirements for all equipment. This project deals with alternative control techniques for load voltage stabilization. The technique of tap-changing transformer switched by a relay module in a coupled circuit is used. A microcontroller is used to control the switches to stabilize the load voltage against supply voltage and load current variation. Boosting or bucking effect is performed at low distortion to drive the relay module. The controlled stabilizer can reduce the supply voltage distortion and adjust the load voltage within a very short time. The technical report of this project is available at my [ResearchGate](https://www.researchgate.net/publication/318654258_Microcontroller_Based_Voltage_Stabilizer). The hardware testing video is available at my [Youtube](https://www.youtube.com/watch?v=p4Uw0DTCDqE&list=PLjNoIGauJyXgEuwqo5jd31XItulT7CI-5&index=5).

---
## Table of Contents
- [Microcontroller Based Voltage Stabilizer](#microcontroller-based-voltage-stabilizer)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Specifications of Components](#specifications-of-components)
  - [|   14.     | Bulb (Load)        | 60 Watt, 210 ~ 240V (50 Hz)   | 1 Unit |](#---14------bulb-load---------60-watt-210--240v-50-hz----1-unit-)
  - [Circuit Diagram](#circuit-diagram)
  - [Hardware Images](#hardware-images)
    - [*Voltage Sampling Circuit*](#voltage-sampling-circuit)
    - [*Wiring of the Transformer*](#wiring-of-the-transformer)
    - [*Wiring of the Relay Module*](#wiring-of-the-relay-module)
    - [*Final Hardware*](#final-hardware)

   - [Summary of Results](#summary-of-results)
- [Microcontroller Based Voltage Stabilizer](#microcontroller-based-voltage-stabilizer)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Specifications of Components](#specifications-of-components)
  - [|   14.     | Bulb (Load)        | 60 Watt, 210 ~ 240V (50 Hz)   | 1 Unit |](#---14------bulb-load---------60-watt-210--240v-50-hz----1-unit-)
  - [Circuit Diagram](#circuit-diagram)
  - [Hardware Images](#hardware-images)
    - [*Voltage Sampling Circuit*](#voltage-sampling-circuit)
    - [*Wiring of the Transformer*](#wiring-of-the-transformer)
    - [*Wiring of the Relay Module*](#wiring-of-the-relay-module)
    - [*Final Hardware*](#final-hardware)
  

___
## Getting Started
This project analyses a different stabilizing topology and a different design based on tapping the relay for different supply voltages. The purpose is to achieve a nearly 220V value for each variation of supply to drive the load risk freely, thus stabilizing the output voltage. 

The **process chart** is as follows: 

![Microcontroller-Based-Voltage-Stabilizer](./images/Picture1.png)

---
## Specifications of Components
The required **components** are as follows:

| Serial No.| Components | Specifications | Quantity |
|:---------:|:----------:|:--------------:|:--------:|
|   1.      | Diode      | 1N4007         | 4 Unit |
|   2.      | Resistor   | 1KΩ , 2KΩ      | 1 Unit Each |
|   3.      | Capacitor  | 10 uf      | 1 Unit |
|   4.      | AC Supply (VARIAC)     | 180 V ~ 230 V (50 Hz)                            | 1 Unit |
|   5.      | Transformer            | i/p : 220 V (50 Hz) ,  o/p : 6*2 V (600 mA)        | 1 Unit |
|   6.      | Tap Changing Transformer            | i/p : 180 V - 230 V (50 Hz),  o/p : 220 V (2 A)        | 1 Unit |
|   7.      | Arduino Board            | Nano       | 1 Unit |
|   8.      | Bulk Converter          | i/p : 12 V (DC) , o/p : 5 V (DC)      | 1 Unit |
|   9.      | Relay Module          | 8 Relay Module (Operating Voltage: 5V DC)    | 1 Unit |
|   10.     | LED (Red)         | 1.8 V    | 1 Unit |
|   11.     | Bread Board        |     | 1 Unit |
|   12.     | Chords and wires       |     | |
|   13.     | Digital Multimeter       |     | 1 Unit |
|   14.     | Bulb (Load)        | 60 Watt, 210 ~ 240V (50 Hz)   | 1 Unit |
---

## Circuit Diagram
![Microcontroller-Based-Voltage-Stabilizer](./images/Picture2.PNG)

---
## Hardware Images
### *Voltage Sampling Circuit*

---
![Microcontroller-Based-Voltage-Stabilizer](./images/Picture3.jpg)

---
### *Wiring of the Transformer*

![Microcontroller-Based-Voltage-Stabilizer](./images/Picture4.jpg)

---
### *Wiring of the Relay Module*

![Microcontroller-Based-Voltage-Stabilizer](./images/Picture5.jpg)

---
### *Final Hardware*

![Microcontroller-Based-Voltage-Stabilizer](./images/Picture6.jpg)

---