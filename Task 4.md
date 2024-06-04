# Project Tittle : 
## MicroSpeak: Efficient Speech-to-Text on the CH32V003

## Overview
MicroSpeak is a cutting-edge project that demonstrates the power of the affordable CH32V003 microcontroller in creating a streamlined speech-to-text application. By integrating the MAX4466 microphone amplifier with the CH32V003 Development Board, and using the WCH-LinkE adaptor, MicroSpeak offers an efficient solution for audio processing tasks. This setup highlights the potential of the CH32V003 for budget-conscious developers who require effective and reliable speech recognition capabilities.

The project is designed to showcase the following:

- **Cost-Effectiveness:** Utilizing the CH32V003 microcontroller, known for its affordability, making advanced technology accessible.
- **Integration:** Seamlessly combining the MAX4466 microphone amplifier with the CH32V003 board to capture and process audio inputs.
- **Efficiency:** Demonstrating the microcontroller's ability to handle speech-to-text tasks efficiently, suitable for various applications including IoT devices, low-cost personal assistants, and other audio-based interfaces.
- **Simplicity:** Providing a clear and concise setup that can be replicated easily, supporting developers in creating their own speech-to-text systems without extensive resources.

## Components Required
- CH32V003 Development Board
- MAX4466 Microphone Amplifier
- WCH-LinkE Adaptor

## Circuit Connection
1. Connect the VCC of the Link-E Adaptor to the 3V3 pin on the CH32V003 Dev Board.
2. Connect the GND of the Link-E Adaptor to the GND pin on the CH32V003 Dev Board.
3. Connect the SWDIO/TMS pin of the Link-E Adaptor to the PD1 pin on the CH32V003 Dev Board.
4. Connect the RX pin of the Link-E Adaptor to the PD5 pin on the CH32V003 Dev Board.
5. Connect the VCC of the MAX4466 Microphone to the VCC pin on the CH32V003 Dev Board.
6. Connect the GND of the MAX4466 Microphone to the GND pin on the CH32V003 Dev Board.
7. Connect the OUT of the MAX4466 Microphone to the PD4 pin on the CH32V003 Dev Board.

## Pinout Diagram
![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/4b637307-07dd-4476-ab31-726524fd2a63)

## Table for Pin Connections

| Link-E Adaptor     | CH32V003 Dev Board |
| ------------------ | ------------------ |
| 3V3                | VCC                |
| GND                | GND                |
| SWDIO/TMS          | PD1                |
| RX                 | PD5                |

| MAX4466 Microphone | CH32V003 Dev Board |
| ------------------ | ------------------ |
| VCC                | VCC                |
| GND                | GND                |
| OUT                | PD4                |
