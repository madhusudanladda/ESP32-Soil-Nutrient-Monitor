# ESP32 Soil Nutrient Monitor

An ESP32-based soil monitoring project using RS485 communication to interface with a soil sensor and acquire soil parameters for real-time monitoring.

## Features

- ESP32-based embedded controller
- RS485 sensor communication
- Modbus-oriented communication
- Soil parameter data acquisition
- UART communication
- Serial Monitor debugging
- Modular sensor interface

## Hardware

- ESP32
- RS485 Transceiver
- RS485 Soil Sensor
- Jumper Wires

## Technologies

- Embedded C/C++
- ESP32
- RS485
- UART
- Modbus
- Sensor Interfacing
- GPIO

## RS485 Pin Configuration

| RS485 | ESP32 |
|---|---|
| RX | GPIO 16 |
| TX | GPIO 17 |
| DE/RE | GPIO 4 |

## Serial Monitor Output

ESP32 Soil Nutrient Monitor

RS485 interface initialized.

Baud rate: 4800

Slave ID: 1

RS485 request sent. Awaiting sensor response...

RS485 request sent. Awaiting sensor response...

RS485 request sent. Awaiting sensor response...

Sensor Output

Moisture : 42.8 %

Temp     : 28.1 C

pH       : 6.7

N        : 92 mg/kg

P        : 38 mg/kg

K        : 115 mg/kg
