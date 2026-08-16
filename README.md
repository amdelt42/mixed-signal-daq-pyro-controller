# Mixed-Signal DAQ & Pyrotechnic Control System

This repository contains the [firmware / hardware design] for an STM32-powered data acquisition board.

## Key Features

* **Microcontroller:** STM32 core managing real-time loops, sensor aggregation, and firing logic.
* **Analog Front End:** 
  * Full-bridge strain gauge and Thermocouple measurement signal blocks with dedicated filtering.
  * Local digital temperature sensor for real-time Cold-Junction Compensation (CJC).
  * High-resolution Analog-to-Digital Converter (ADC).
* **Actuation:** Integrated pyrotechnic firing channels.
* **Telemetry & Comms:** High bit-rate CAN FD transceiver for high-bandwidth data output.

