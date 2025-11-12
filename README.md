# Smart Aquarium IoT Project

### Team Members
- **Showrish** – VU21CSEN0600005
- **Suhash** – VU21CSEN0600011
- **Dhanush** – VU21CSEN0600121

---

## 1. Introduction
The Smart Aquarium is an IoT-based project that automates the monitoring and maintenance of aquariums. It uses sensors, microcontrollers, and automation systems to ensure the health and well-being of aquatic life while minimizing human intervention.

---

## 2. Purpose
The purpose of this project is to implement a smart solution for aquarium maintenance, enabling remote monitoring of water levels, lighting, and feeding schedules. This reduces manual tasks and enhances the overall care of aquatic environments.

---

## 3. Scope
The project focuses on the integration of IoT devices with aquariums, explaining how sensors and automation systems work together to maintain optimal conditions. The system supports real-time monitoring, remote control, and automated tasks such as lighting adjustments and fish feeding.

---

## 4. Components Used

| Component | Description |
|------------|-------------|
| **NodeMCU ESP8266** | Main IoT controller responsible for processing sensor data and controlling devices. |
| **Water Level Sensor** | Measures the water levels in the aquarium, providing real-time data. |
| **LDR Sensor** | Detects ambient light levels and adjusts aquarium lighting accordingly. |
| **Servo Motor** | Controls the feeding mechanism, dispensing food at set intervals. |
| **Jumper Wires & Breadboard** | Used for connecting and prototyping circuits without soldering. |

---

## 5. Working

### Water Level Monitoring
The water level sensor monitors the tank’s water level, triggering notifications when the level drops below a specified threshold.

### Lighting Control
The LDR sensor tracks ambient light conditions and adjusts the internal lighting to ensure a stable environment for the fish.

### Automated Feeding
The servo motor automates the feeding process, dispensing food at predetermined times to maintain the fish’s feeding schedule.

---

## 6. Software and Services Used

| Software / Service | Purpose |
|--------------------|----------|
| **ThingSpeak** | Platform used for collecting, storing, and visualizing sensor data in real-time. |
| **IFTTT (If This Then That)** | Automates notifications by sending email alerts when conditions such as low water levels occur. |
| **Arduino IDE** | Used for writing and uploading code to the NodeMCU ESP8266. |
| **WordPress** | Provides a web interface to monitor aquarium conditions and manage sensor data. |

---

## 7. Protocols Used

| Protocol | Function |
|-----------|-----------|
| **SMTP (Simple Mail Transfer Protocol)** | Sends email alerts via Gmail when specific triggers like low water levels are detected. |
| **HTTP (Hypertext Transfer Protocol)** | Enables communication between sensors and ThingSpeak for real-time data collection and control. |
| **Internet Protocol (IP)** | Transmits sensor data to online platforms such as ThingSpeak and IFTTT. |
| **PHP and HTML** | Used in WordPress to manage and present sensor data through the web interface. |

---

## 8. Data Collection and Communication

- **ThingSpeak:** Serves as the central hub for gathering data from sensors (water level, LDR, and servo motor) for real-time monitoring and visualization.
- **IFTTT:** Monitors specific conditions, such as low water levels, and triggers email notifications to ensure timely corrective actions.

---

## 9. Database Website Using WordPress
The WordPress site integrates PHP, MySQL, and HTML for dynamic content management and database storage. It stores and retrieves sensor data from the aquarium, allowing users to analyze and monitor conditions through a user-friendly web interface.

---

## 10. Outputs

| Output | Description |
|---------|-------------|
| **Real-time Data Visualization** | Displays water levels, lighting conditions, and feeding schedules on a dashboard. |
| **Automated Alerts** | Sends email notifications when issues such as low water levels are detected. |
| **Automated Actions** | Performs scheduled tasks such as adjusting lighting or feeding fish based on real-time data. |

---

## 11. Conclusion
The Smart Aquarium project successfully automates the maintenance and monitoring of aquariums using IoT technology. It ensures that aquatic life thrives in optimal conditions through real-time monitoring, automated feeding, and lighting control. This reduces manual intervention and provides an efficient, technology-driven solution for aquarium enthusiasts.

---

## 12. References
- [ThingSpeak](https://thingspeak.com/)
- [WordPress](https://wordpress.com/)
