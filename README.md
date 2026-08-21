# Voice and AI-Enabled Intelligent Robot Controller PCB

A custom **4-layer embedded robotics controller PCB** designed for a multifunctional voice-interactive robot. The board integrates motor control, servo control, voice recognition, AI audio interaction, environmental monitoring, RGB indication, and dedicated interfaces into a compact custom-designed PCB.

## Features

* **ESP32-based main controller**
* **Dual DC motor control** using TB6612FNG
* **3 servo motor interfaces** for robotic movement and hand mechanisms
* **VC-02 AI Thinker voice recognition module** for offline voice commands
* **ICS-43434 digital microphone** for AI chatbot voice input
* **MAX98357A I2S audio amplifier** for audio output
* **Gemini AI chatbot interface** for online conversational interaction
* **WS2812 RGB LEDs** for status and visual indication
* **Temperature monitoring**
* **Automatic DC cooling fan control** based on temperature
* **Buzzer** for temperature and alert indication
* **USB-C programming interface** using CH340C
* Dedicated motor, servo, and system power distribution

## PCB Design

The PCB uses a **4-layer stackup**:

| Layer | Function            |
| ----- | ------------------- |
| L1    | Signal + Components |
| L2    | Solid GND Plane     |
| L3    | Power Distribution  |
| L4    | Signal              |

The multilayer design provides improved grounding, power distribution, signal integrity, and routing flexibility for the mixed-signal robotics system.

## Main Components

* ESP32 Controller Module
* TB6612FNG Motor Driver
* VC-02 AI Thinker Voice Recognition Module
* ICS-43434 MEMS Microphone
* MAX98357A I2S Audio Amplifier
* CH340C USB-to-UART
* WS2812 RGB LEDs
* Temperature Sensor
* DC Cooling Fan
* Buzzer
* Servo and DC Motor Connectors
* USB Type-C Connector
* Power Regulation and Filtering Components

## Applications

The controller is designed for:

* Voice-controlled robotics
* AI-assisted human-machine interaction
* Educational robotics
* Embedded AI systems
* Interactive robotic platforms
* Custom robotic control systems

## Design Tools

* **KiCad**
* Schematic Capture
* PCB Layout
* 4-Layer PCB Routing
* Design Rule Checking (DRC)
* 3D PCB Visualization
