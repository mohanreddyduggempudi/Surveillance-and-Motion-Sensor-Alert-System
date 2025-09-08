# Surveillance-and-Motion-Sensor-Alert-System

1. Aim 
To design and implement a surveillance-based motion sensor alert system that detects 
motion and promptly notifies the user through a simulated IoT network using Cisco 
Packet Tracer. 

2. Problem Statement 
In many industrial and residential settings, ensuring safety and monitoring premises is 
critical. Traditional surveillance systems lack real-time automated notifications when 
motion is detected. 
The problem is to integrate motion detection sensors with an IoT-enabled alert system 
that: 
Detects motion in a monitored zone. 
Sends an immediate alert notification to the user via IoT infrastructure. 
Ensures reliable surveillance without requiring continuous manual monitoring. 

3. Scope of the Solution 
Industrial Applications: Monitor restricted zones, factory equipment areas, and 
warehouses. 
Residential Applications: Enhance home security with smart surveillance and intruder 
alerts. 
Scalability: Can integrate additional IoT devices (sensors, cameras, alarms) for larger 
deployments. 
Future Extension: Integration with cloud IoT platforms, SMS/email alerts, and mobile 
applications for remote monitoring. 

4. Required Components 
Software 
Cisco Packet Tracer (CPT) → To simulate IoT devices, sensors, and network. 
IDE: (Optional, if extending with scripts) Python IDE such as PyCharm or VS Code for IoT 
logic simulation. 
Hardware (Simulated in CPT) 
Motion Detection Sensor (PIR sensor in IoT device list) 
Surveillance Camera (IoT Camera in CPT) 
IoT Home Gateway (to connect devices to server) 
Smart Device for Notification (PC/Tablet/Smartphone) 
Server (for storing logs / sending alerts) 
Alarm/Siren (optional, for local alerting) 

5. Simulated Circuit 
The circuit diagram can be designed in Cisco Packet Tracer using IoT devices: 
Connect PIR Motion Sensor → Home Gateway 
Connect Camera → Home Gateway 
Configure IoT Server to receive notifications 
Configure User Device (PC/Tablet/Phone) for alerts 
(Upload the CPT file to GitHub and attach a screenshot of the circuit in your report) 
6. Workflow of the System 
1. Motion is detected by the PIR Motion Sensor. 
2. The Home Gateway receives the sensor trigger. 
3. An alert signal is sent to the IoT server. 
4. The server notifies the user via their device (PC/Tablet/Phone). 
5. (Optional) An alarm or siren is activated in case of motion detection. 
