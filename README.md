# Fire and Smoke Detection System

## Overview
The **Fire and Smoke Detection System** is a hardware prototype designed to detect fire and smoke hazards using Arduino Uno. The system integrates sensors and a Bluetooth module to monitor the environment, sound alarms, and send hazard notifications to smartphones. This project was developed as part of the **CSE360: Computer Interfacing** course.

## Project Objectives
- Develop a reliable and cost-effective fire and smoke detection system.
- Ensure early detection of fire and smoke to prevent loss of life and property.
- Provide real-time hazard notifications to occupants via smartphones.

## Features
1. **Fire and Smoke Detection**:
   - Flame detection using a flame sensor.
   - Smoke and gas detection using an MQ-2 Gas & Smoke sensor.

2. **Alerts and Notifications**:
   - Alarm system to alert occupants in case of fire or smoke.
   - Hazard notifications sent to smartphones via an HC-05 Bluetooth module.

3. **Real-Time Monitoring**:
   - Continuous monitoring of the environment to detect fire hazards promptly.

## Components Used
- **Arduino Uno**: Microcontroller for system control and integration.
- **Flame Sensor**: Detects fire or flame.
- **MQ-2 Gas & Smoke Sensor**: Detects smoke and flammable gases.
- **HC-05 Bluetooth Module**: Sends hazard notifications to smartphones.
- **Buzzer**: Sounds an alarm in case of hazard detection.
- **LEDs**: Indicates system status.
- **Power Supply**: Provides necessary power to the system.

## How It Works
1. The flame sensor and MQ-2 sensor continuously monitor the environment for fire and smoke.
2. If fire or smoke is detected:
   - The system triggers an alarm using the buzzer.
   - LEDs light up to indicate the detection.
   - A notification is sent to a smartphone via the HC-05 Bluetooth module.

3. The system resets once the hazard is cleared.

## Installation and Setup
1. **Hardware Setup**:
   - Connect the flame sensor, MQ-2 sensor, buzzer, and HC-05 module to the Arduino Uno as per the circuit diagram.
   - Ensure proper power supply connections.

2. **Software Setup**:
   - Install the Arduino IDE on your computer.
   - Upload the provided sketch to the Arduino Uno.
   - Pair the HC-05 module with your smartphone.

3. **Testing**:
   - Test the sensors by introducing flame or smoke near the sensors.
   - Verify that the buzzer, LEDs, and Bluetooth notifications work as expected.

## Use Cases
- Residential fire safety.
- Industrial fire monitoring.
- Early warning systems for public spaces.

## Benefits
- **Cost-Effective**: Uses readily available and affordable components.
- **Reliable**: Provides real-time alerts for fire hazards.
- **User-Friendly**: Simple setup and operation.

## Future Improvements
- Integration with IoT for remote monitoring and notifications.
- Addition of temperature sensors for enhanced detection.
- Development of a dedicated mobile application for alerts.

## Acknowledgments
This project was completed as part of the **CSE360: Computer Interfacing** course, with guidance and support from our instructor and peers.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code and hardware design as needed.

---

**Developed by:** Sartaj Emon Prattoy and Team

