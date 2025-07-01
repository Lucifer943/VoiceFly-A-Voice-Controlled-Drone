🚁 VoiceFly – Voice Controlled Drone
VoiceFly is a Bluetooth-based voice-controlled drone developed using Arduino UNO and the HC-05 Bluetooth module. This project enables wireless control of drone movements through voice commands, allowing hands-free navigation and basic maneuvering functions. It combines embedded programming, electronics, and speech interaction into a compact, real-time embedded system.

🎯 Objective
The primary goal of VoiceFly is to create a low-cost, efficient, and responsive drone system that can interpret and execute basic flight commands via voice. It is designed for educational and experimental purposes to explore the integration of embedded systems with voice interfaces.

🔧 Key Features
🎙️ Voice Command Control: Accepts 6 essential voice commands—start, stop, forward, backward, speed up, and slow down.

📶 Bluetooth Connectivity: Utilizes the HC-05 module for seamless communication between an Android device and the drone.

⚙️ Real-time Response: Executes commands with an average delay of under 1.5 seconds after voice recognition.

🧪 Tested Reliability: Successfully tested across 15+ flight sessions to ensure system responsiveness, safety, and command accuracy.

🔐 Secure Control: Only recognized paired devices can control the drone, minimizing accidental triggers.

🧠 Technologies & Components Used
🔌 Hardware
Arduino UNO – Microcontroller unit to control the drone logic

HC-05 Bluetooth Module – Wireless communication interface

L298N Motor Driver – Controls the rotation and direction of DC motors

DC Motors with Propellers – Used for drone propulsion

Li-Po Battery (11.1V) – Power supply

Chassis and Frame – Custom-built lightweight frame for lift and stability

💻 Software
Arduino IDE – Used for programming and uploading firmware

C/C++ – Core language used for logic implementation

Android Voice Command App – Converts spoken commands into serial signals sent over Bluetooth

📈 Performance
✅ Recognized commands with 95% accuracy in low-noise environments

⚡ Response time from voice to motion: ~1.2 seconds

🧪 Flight stability maintained in 10-minute sessions with consistent responsiveness

🛠️ How It Works
The Android app receives a voice command from the user.

The command is translated into a serial message and transmitted via Bluetooth.

The HC-05 module receives this message and passes it to the Arduino.

The Arduino processes the instruction and sends the appropriate control signals to the motor driver.

The motors execute the desired movement (e.g., forward, stop, etc.).

🌱 Future Enhancements
🤖 Google Assistant / IFTTT Integration for cloud-based voice control

📱 Custom Android App with GUI-based voice control and command history

🛰️ GPS Module for predefined route flying and geofencing

📷 Camera Integration for FPV (First-Person View) monitoring
