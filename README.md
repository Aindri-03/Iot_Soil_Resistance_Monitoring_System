🌱 IoT-Based Smart Agriculture and Environmental Monitoring System








---

📌 Project Overview

This project implements an IoT-based sensing and data acquisition system for agriculture and environmental applications.
It enables real-time soil moisture monitoring and automated irrigation, helping farmers optimize water usage and improve crop yield.


---

⚙ Features

🌍 Real-time soil moisture monitoring

💧 Automated irrigation based on soil conditions

📊 Sensor data logging and visualization on Serial Monitor

📡 IoT-enabled system (supports GSM/cloud integration)

🔌 Supports single or multiple soil sensors



---

🛠 Tech Stack

Hardware: Arduino UNO R3, FC-28 Soil Moisture Sensor, Jumper Wires, Power Supply

Software: Arduino IDE (C/C++), Serial Monitor

IoT Connectivity: GSM Shield (optional for cloud communication)



---

📐 System Workflow

1. Soil Moisture Sensors are connected to Arduino.


2. Arduino reads sensor data (Analog/Digital).


3. System compares values with thresholds.


4. Soil condition is classified as:

Dry 🌵

Medium Moisture 🌿

Wet 💦

High Moisture 🌊



5. Multiple sensors supported for diverse soil monitoring.




---

🚀 Results

✅ Built a working prototype for smart farming.
✅ Automated irrigation demonstrated successfully.
✅ Graphical analysis verified accuracy across different soil conditions.


---

📂 Repository Structure

/Code
   └── SingleSensor.ino
   └── MultiSensor.ino
/Hardware
   └── CircuitDiagram.png
   └── ComponentsList.md
/Results
   └── SerialMonitorLogs.txt
   └── Graphs.png
README.md


---

⚡ Installation & Setup

⿡ Clone the Repository

git clone https://github.com/your-username/IoT-Agriculture-System.git
cd IoT-Agriculture-System

⿢ Open Code in Arduino IDE

Go to /Code folder

Open either SingleSensor.ino or MultiSensor.ino


⿣ Connect Hardware

Arduino UNO with FC-28 Soil Moisture Sensors

Jumper wires for connections

(Optional) GSM Shield for IoT integration


⿤ Upload & Monitor

Select correct COM Port in Arduino IDE

Upload code to Arduino

Open Serial Monitor to view results



---

🧪 Usage Example

When soil is dry:

Sensor_data: 980
No moisture, Soil is dry

When soil has some moisture:

Sensor_data: 450
Soil has some moisture


---

🤝 Contribution Guidelines

Contributions are welcome! 🚀
To contribute:

1. Fork this repo


2. Create a new branch (feature-xyz)


3. Commit changes (git commit -m 'Added new feature')


4. Push to your branch


5. Open a Pull Request 🎉




---

📜 License

This project is licensed under the MIT License – feel free to use, modify, and distribute.# Iot_Soil_Resistance_Monitoring_System
