# IoT-Enabled Swarm Robot Coordination

An IoT-enabled swarm robotics project based on ESP32, ESP-NOW wireless communication, ultrasonic sensing, and Leader–Follower coordination.

The project demonstrates coordinated robotic operation for a smart parking application. A Leader ESP32 acts as the control and decision-making unit, while a Follower ESP32 controls the robot, detects parking-slot availability, and communicates the detected information back to the Leader.

## Key Technologies

- ESP32
- ESP-NOW
- Blynk IoT
- HC-SR04 Ultrasonic Sensor
- Nokia 5110 LCD
- L298N Motor Driver
- DC Motors
- Arduino IDE
- Embedded C/C++

## Main Features

- Leader–Follower robot coordination
- Wireless ESP-NOW communication
- Real-time parking-slot detection
- Ultrasonic sensor-based sensing
- Automated robot movement
- IoT-based control through Blynk
- LCD-based system status display
- Automatic parking-slot selection
- Scalable architecture for multiple follower robots

## System Architecture

The system consists of:

**Leader Robot / Control Unit**
→ Receives commands  
→ Processes slot information  
→ Selects an available slot  
→ Displays information on LCD  
→ Sends commands to the Follower

**Follower Robot / Execution Unit**
→ Receives commands through ESP-NOW  
→ Moves between parking slots  
→ Detects slot availability using ultrasonic sensing  
→ Sends slot status back to the Leader

## Future Scope

The system can be extended to multiple follower robots, enabling parallel operation and larger-area coverage, forming a scalable swarm-based robotic system.
