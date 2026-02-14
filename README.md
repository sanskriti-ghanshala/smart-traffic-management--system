# smart-traffic-management--system
AI-based Smart Traffic Management System
Smart Traffic Management System (AI-Based)
   An AI-powered Smart Traffic Management System that simulates a real-time traffic intersection and dynamically controls traffic signals based on vehicle density and emergency vehicle detection. The system uses computer vision and object detection to improve traffic flow and give priority to ambulances.

📌 Project Overview

This project simulates a 4-way traffic intersection using Python and Pygame. It uses an AI vehicle detection model (YOLOv8) to detect vehicles from camera input and adjust signal timings automatically. If an ambulance is detected, the system immediately gives it signal priority.
The goal is to reduce congestion and improve emergency response time using AI-driven traffic control.

⚙️ Features

🚗 Real-time traffic simulation
🧠 AI-based vehicle detection using YOLOv8
🚑 Automatic ambulance priority handling
⏱️ Dynamic green signal timing based on vehicle count
🎮 Visual simulation using Pygame
📷 Camera-based detection support (OpenCV)
🔁 Multi-lane, multi-direction traffic flow
📊 Vehicle count and timing statistics

🛠️ Tech Stack
Python
Pygame
OpenCV
NumPy
YOLOv8 (Ultralytics)
Threading

▶️ How to Run                                                                                                                                                                                            
pip install -r requirements.txt

2️⃣ Run the project                                                                                                                                                                                                  
python hello.py


🧪 How It Works
Vehicles are generated in different lanes and directions.
The simulator tracks vehicle queues at each signal.
YOLOv8 detects vehicles (and ambulances) from camera frames.
Signal timing is calculated dynamically.

If an ambulance is detected:
That lane gets immediate green signal
Ambulance speed is increased in simulation
Green time is extended.

🎯 Applications
Smart city traffic systems
Emergency vehicle routing
AI-based urban planning
Traffic congestion reduction research
