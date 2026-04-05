PC Vitals Cloud Monitor 🖥️☁️
A lightweight Python-based IoT application that transforms a local workstation into a remote-monitored node. This project captures real-time hardware telemetry and streams it to the ThingSpeak IoT Cloud for live visualization and analysis.

🚀 Overview
In the field of Electronics and Communication Engineering (ECE), monitoring remote systems is critical. This project demonstrates a Software-in-the-Loop (SIL) approach to IoT, using a PC as a data source to understand cloud integration, REST APIs, and system-level resource management.

🛠️ Features
Real-time Telemetry: Captures CPU usage, RAM consumption, and Battery health.

Cloud Integration: Uses ThingSpeak's REST API for data logging.

Live Dashboard: Visualizes hardware performance through interactive web charts.

Automated Updates: Configured for 15-second intervals to comply with ThingSpeak Free Tier limits.

Robust Connectivity: Includes error handling for network latency and connection drops.

🧰 Tech Stack
Language: Python 3.x

Libraries: * psutil: For cross-platform hardware monitoring.

requests: For handling HTTP/API communication.

Cloud Platform: ThingSpeak IoT# PC-Vitals-IoT-Monitor
