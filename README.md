# Design and Implementation of a Multi-Sensor Module to communicate with the Central Data Server and to analyse and process the collected data.
This project represents designing and implementing a multi-sensor module which includes NodeMCU(ESP8266) and various air quality sensors to communicate with a central data server for data storage and analysis. The NodeMCU (ESP8266) microcontroller integrates with various sensors to monitor environmental parameters like carbon dioxide, nitrogen dioxide, Volatile Organic Matter, Particulate Matter, Temperature, and Humidity.
The Communication is established via the MQTT protocol, ensuring efficient and reliable data transmission to a central Raspberry Pi server using the Internet. The collected data is stored in a MariaDB database and values are visualized through Grafana for real-time monitoring. 
The system’s design emphasizes scalability, cost-effectiveness, and ease of deployment, making it suitable for diverse applications such as smart homes, industrial automation and environmental monitoring. A prototype PCB is designed using Altium ECAD software for robust and durable deployment.

# Hardware
1. Sensirion SCD41 CO2 sensor
2. Sensirion SPS30 Particluate Matter sensor
3. Sensirion SVM41 sensor
4. Adafruit LIS3DH Triple Axis Accelerometer
5. Grove seeed Loudness sensor
6. NodeMCU(ESP8266)
7. Raspberry Pi 4 model B

# Software
1. Arduino IDE (for NodeMCU(ESP8266) programming)
2. Raspberry Pi OS
3. MariaDB
4. phpMyAdmin
5. Apache2
6. Grafana Dashboard
7. Altium Designer
