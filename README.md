
# Hardware

This repo holds our PCB schematics and PCB design and is used for version control of PCBs.

## PCB design directory

The directory holds the **Project_Libraries** and schematics and PCB design.

Thr Project Libraries folder contains custom symbols and footprints of the sensors used. The component used can be found within the Home.csv file. that is the BOM.

## Bill of Materials

The components needed to replicate this PCB and project are:

- 1 ESP32 DEVKIT V1 microcontroller
- 2 LM2596 Buck converters
- 1 Buzzer
- 1 RGB LED (or three  LEDs, note to add resistors if used)
- 7 2-pin screw terminal blocks
- 2 3-pin screw terminal blocks
- 1 ACS712_5B sensor (current sensor)
- 1 DHT11 sensor (Temperature and Humidity)
- 1 PIR sensor (motion sensor)
- 1 MQ2 sensor (gas sensor)

There are components attatched to the PCB externally:

- 1 Fan
- 1 LCD with I2C
- 1 EM Lock
- 1  RFID card reader (RFC522)
- 12V power supply
