
Smart Aquarium IoT Project
Showrish VU21CSEN0600005 
Suhash VU21CSEN0600011
Dhanush VU21CSEN0600121

1.	Introduction
The Smart Aquarium is an IoT-based project that automates the monitoring and maintenance of aquariums. It utilizes sensors, microcontrollers, and automation systems to ensure the health and well-being of aquatic life while minimizing human intervention.

2.	Purpose
The purpose of this project is to implement a smart solution for aquarium maintenance, enabling remote monitoring of water levels, lighting, and feeding schedules. This reduces manual tasks and enhances the overall care of aquatic environments.

3.	Scope
The project focuses on the integration of IoT devices with aquariums, offering a detailed explanation of how sensors and automation systems work together to maintain optimal aquarium conditions. The system supports real-time monitoring, remote control, and automated tasks such as lighting adjustments and ﬁsh feeding.
 
4.	Components Used in the Project
●	NodeMCU ESP8266:
Main IoT controller for the project, responsible for processing sensor data and controlling devices.
●	Water Level Sensor:
Measures the water levels in the aquarium, providing real-time data.
●	LDR Sensor:
Detects ambient light levels and adjusts the aquarium lighting accordingly.
●	Servo Motor:
Controls the feeding mechanism, dispensing food at set intervals.
●	Jumper Wires & Breadboard:
Used for connecting and prototyping the circuit without soldering.

5.	Working
●	Water Level Monitoring:
The water level sensor monitors the tank’s water level, triggering notiﬁcations when the water drops below a speciﬁed threshold.
●	Lighting Control:
The LDR sensor tracks ambient light conditions and adjusts the internal lighting to ensure a stable environment for the ﬁsh.
●	Automated Feeding:
The servo motor automates the feeding process, dispensing
 
food at predetermined times to maintain the ﬁsh's feeding schedule.

6.	Softwares and Services Used
●	ThingSpeak:
A platform used for collecting, storing, and visualizing sensor data in real-time.
●	IFTTT (If This Then That):
Automates notiﬁcations by sending email alerts when certain conditions are met, such as low water levels.
●	Arduino IDE:
Used for writing and uploading code to the NodeMCU ESP8266 microcontroller.
●	WordPress:
Provides a web interface to monitor the aquarium’s conditions and manage sensor data.

7.	Protocols Used
●	SMTP (Simple Mail Transfer Protocol):
Used for sending email alerts via Gmail when speciﬁc triggers, like low water levels, are detected.
●	HTTP (Hypertext Transfer Protocol):
Enables communication between the sensors and ThingSpeak for real-time data collection and control.
●	Internet Protocol (IP):
Utilized for transmitting sensor data to online platforms like ThingSpeak and IFTTT.
 
●	PHP and HTML:
These protocols are employed within WordPress to manage and present sensor data on a web interface.

8.	Data Collection and Communication
●	ThingSpeak:
Serves as the central hub for gathering data from the water level sensor, LDR sensor, and servo motor, allowing for
real-time monitoring and visualization of the aquarium's environment.
●	IFTTT:
Monitors speciﬁc conditions, such as low water levels, and triggers email notiﬁcations to ensure timely corrective actions.

9.	Database Website Using WordPress
The WordPress site integrates PHP, MySQL, and HTML for dynamic content management and database storage. It is designed to store and retrieve sensor data from the aquarium, allowing users to analyze and monitor the conditions from a user-friendly web interface.


10.	Outputs
●	Real-time Data Visualization:
Displays water levels, lighting conditions, and feeding schedules on a dashboard for the user.
●	Automated Alerts:\
Sends email alerts when the system detects issues, such as low water levels, requiring immediate attention.
●	Automated Actions:
Performs scheduled tasks like adjusting the lighting or feeding the ﬁsh based on real-time data.

11.	Conclusion
 
The Smart Aquarium project successfully automates the maintenance and monitoring of aquariums using IoT technology. The system ensures that aquatic life thrives in optimal conditions through real-time monitoring, automated feeding, and lighting control. This reduces manual intervention and provides an eﬃcient, tech-driven solution for aquarium enthusiasts.

12.	References
●	https://thingspeak.com/
●	https://wordpress.com/
