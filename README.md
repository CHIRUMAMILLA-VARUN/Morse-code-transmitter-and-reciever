# Morse Code Transmitter and Receiver

## Project Description
This project demonstrates a wireless Morse code communication system using an Arduino Uno, ESP32, and ESP8266. The system allows Morse code input to be translated into text, transmitted over Wi-Fi, and received remotely.

## System Overview
- The **Arduino Uno** reads Morse code input (e.g., via button or signal), decodes it into text, and sends the message to the **ESP32** via UART.
- The **ESP32** receives the decoded text and transmits it wirelessly to the **ESP8266** using Wi-Fi.
- The **ESP8266** acts as a receiver, displaying or processing the incoming message.

## Key Features
- **Morse Code Decoding**: Arduino Uno interprets Morse code signals and converts them into readable text.
- **UART Communication**: Serial communication between Arduino Uno and ESP32.
- **Wi-Fi Transmission**: ESP32 sends the decoded message over Wi-Fi to the ESP8266.
- **Remote Reception**: ESP8266 receives and displays the message.

## Technologies Used
- **Hardware**: Arduino Uno, ESP32, ESP8266
- **Communication**: UART (Arduino to ESP32), Wi-Fi (ESP32 to ESP8266)
- **Software**: Arduino IDE, ESP libraries for Wi-Fi communication

## What I Learned
- Implemented UART communication between microcontrollers
- Gained experience with Wi-Fi-based data transmission
- Learned to decode Morse code and integrate multiple microcontrollers in a communication pipeline

## Future Scope
- Add encryption for secure message transmission
- Implement a user interface for message input and display
- Expand to bidirectional communication

## Photos


## Acknowledgments
Thanks to my mentors and teammates for their support and collaboration throughout this project.
