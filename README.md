🌊 THESIS TITLE: Real-Time Flood Monitoring and Alert System through the Integration of Wireless Sensor Network and IoT Platform using ESP32 and ThingSpeak

(An IoT-based solution for real-time flood detection, alert, and monitoring using ESP32, ultrasonic sensors, GSM modules, and ThingSpeak integration.)

📖 Description
This project is designed to help communities prepare for and respond to flooding events. The system uses ultrasonic sensors connected to an ESP32 microcontroller to monitor water levels in real time. When water reaches critical thresholds (yellow, orange, red alert levels), the system sends SMS alerts to designated emergency contacts and updates a public dashboard via ThingSpeak. This solution can be deployed in flood-prone areas to provide timely warnings and improve disaster readiness.

🚀 Features
🔴 Real-time flood level detection.
📡 SMS alerting via GSM module (SIM800L)
📊 ThingSpeak integration for live data visualization
🧠 Threshold-based warning system (Yellow, Orange, Red)
⏱️ Delayed alert system to prevent repeated messages within 15 minutes
⬇️ Separate alert for slowly decreasing water levels

🛠️ Tech Stack / Tools Used
- ESP32 Microcontroller
- Ultrasonic Sensor (HC-SR04)
- GSM Module (SIM800L)
- ThingSpeak API
- Arduino IDE
- HTML + CSS (for webpage UI)

JavaScript (for dynamic elements like live time display)

🧪 Installation / Setup
- Clone or Download this repository.
- Wire your components as per the circuit diagram.
- Open the .ino file using the Arduino IDE.
- Set your Wi-Fi credentials and GSM settings in the sketch.
- Upload to ESP32 and monitor via serial.
- Use the included HTML/CSS dashboard to visualize data from ThingSpeak.


👨‍💻 Developers

Web Developer - Mark Joseph Arevalo

Prototype Developers
- Ruzzle Gutierrez
- Mark Joseph Arevalo
- Jon Robert De Pedro
- John Paul Romez
- Peter Paul Montecillo

📜 License
This project is for educational purposes only. Feel free to modify and enhance it for your own use.
