# SSIT_INTERNSHIP
Designed a cloud-connected embedded system using LPC1768 and ESP01 to control devices via ThingSpeak. Implemented UART communication and HTTP parsing to toggle an LED based on real-time cloud commands.
# Embedded ARM Cloud Communication and Control

This project was developed as part of an Embedded Systems internship at SSIT. It showcases a cloud-connected embedded system built using the LPC1768 ARM Cortex-M3 microcontroller and the ESP01 Wi-Fi module. The system allows real-time device control using cloud commands retrieved from the ThingSpeak platform.

##  Project Overview

- The ESP01 connects to a Wi-Fi network and sends HTTP GET requests to a ThingSpeak channel.
- The LPC1768 microcontroller receives the response via UART and parses the JSON data.
- Based on the value of `field1` ("1" or "0"), the LPC1768 toggles an LED ON or OFF.
- The system runs entirely without an RTOS, making it lightweight and suitable for low-power embedded applications.

## 🛠 Technologies & Tools Used

- **Microcontroller**: LPC1768 (ARM Cortex-M3)
- **Wi-Fi Module**: ESP01 (ESP8266 with AT firmware)
- **Communication**: UART
- **Cloud Platform**: ThingSpeak
- **Programming Language**: Embedded C (Keil µVision IDE)
- **Debugging**: QCOM terminal, Flash Magic

##  Features

- Cloud-to-device control using ThingSpeak REST API
- HTTP GET request handling and JSON parsing
- UART-based communication between ESP01 and LPC1768
- LED control demonstration (ON/OFF)
- Expandable architecture for smart automation and industrial IoT use cases

##  Applications

- Smart Home Systems (lights, appliances)
- Industrial Automation
- Smart Agriculture
- IoT-based Learning Platforms
- Remote Device Control

##  Future Scope

- Two-way cloud communication with feedback
- Multi-device control support
- Real-time protocol integration (MQTT, WebSocket)
- Enhanced security features (API key encryption, validation)
- Power optimization for remote/battery-powered deployments

##  Screenshots / Diagrams

> *(You can add your block diagram, circuit diagram, and ThingSpeak graph image here)*

##  Contributors

- **Y. Mahima (SSIT0185)**
- **D. Vani Venkata Priya (SSIT0187)**
- **P. Nithyanand (SSIT0164)**

##  License

This project is for educational and academic purposes under SSIT internship.

---

