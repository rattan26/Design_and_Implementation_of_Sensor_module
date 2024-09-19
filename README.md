# Sensor_module
This thesis projet represents designing and implementing a multi-sensor module to communicate with a central data server for data storage and analysis. The NodeMCU (ESP8266) microcontroller integrates with various sensors to monitor environmental parameters like carbon dioxide, nitrogen dioxide, Volatile Organic Matter, Particulate Matter, Temperature, and Humidity. Communication is established via the MQTT protocol, ensuring efficient and reliable data transmission to a central Raspberry Pi server using the Internet. The collected data is stored in a MariaDB database and visualized through Grafana for real-time monitoring. The system’s design emphasizes scalability, cost-effectiveness, and ease of deployment, making it suitable for diverse applications such as smart homes, industrial automation and environmental monitoring. A prototype PCB is designed using Altium ECAD software for robust and durable deployment.

# sensors used
1. Sensirion SCD41 CO2 sensor
2. Sensirion SPS30 Particluate Matter sensor
3. Sensirion SVM41 sensor
4. Adafruit LIS3DH Triple Axis Accelerometer
5. Grove seeed Loudness sensor

# hardware 
1. NodeMCU(ESP8266)
2. Raspberry Pi 4 model B

# software
1. Arduino IDE
2. Raspberry Pi OS
3. MariaDB
4. phpMyAdmin
5. Apache2

# tool used
1. Grafana Dashboard
2. Altium Designer
