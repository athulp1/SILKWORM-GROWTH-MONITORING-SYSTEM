# SILKWORM_GROWTH_MONITORING_SYSTEM-IOT-MINOR_PROJECT
A monitoring system for silkworm growth incorporates sensors for monitoring temperature,
humidity, and air quality, with data analysis facilitated through a mobile application (APK) and
Firebase. This setup enables users to receive timely alerts regarding any potential issues and
grants remote accessibility, possibly integrating with environmental control systems. By offering
real-time insights into silkworm development, it enhances management practices and contributes
to improved silk production.

## Features
- The objective of a silkworm growth monitoring system is multifaceted, encompassing various
aspects essential for successful cultivation and silk production.
- The system aims to optimize environmental conditions such as temperature, humidity,
and light, along with ensuring the quality and availability of mulberry leaves or artificial diet,
the primary food source for silkworms.
- Continuous monitoring and adjustment of these parameters create an environment
conducive to healthy growth and development throughout the silkworm life cycle.

## Bill of Material

| Serial Number | Name        | Quantity | Price (Rs) |
|---------------|-------------|----------|------------|
| 1             | ESP-32      | 2        | 1000       |
| 2             | PIR Sensor  | 2        | 100        |
| 3             | Tray        | 2        | 240        |
| 4             | Cable       | 1        | 64         |
| 5             | Fan         | 2        | 240        |
| 6             | Wires       | Assorted | 80         |
| 7             | DHT-11      | 2        | 160        |
| 8             | Relay Module| 2        | 200        |
| 9             | LCD Display | 2        | 240        |
| 10            | Motor       | 2        | 200        |
| 11            | I2C         | 2        | 120        |
| 12            | LED         | 6        | 30         |
| 13            | MQ-135      | 2        | 50         |
| 14            | Breadboard  | 4        | 320        |

## Implementaion of the model

![Refernce Circuit](https://github.com/athulp1/SILKWORM-GROWTH-MONITORING-SYSTEM/blob/main/IMPLEMENT.png)

- The ESP32 microcontroller interfacing with various sensors to create a
comprehensive silkworm growth monitoring system. The DHT11 measures temperature and
humidity, the MQ-35 detects gas concentrations, the LDR senses light levels, the PIR identifies
motion, and an ultrasonic sensor measures distance.
These sensors connect to the ESP32 via its GPIO pins, with the ESP32 reading and
processing each sensor’s data. The DHT11 provides crucial information on temperature and
humidity, the MQ-35 ensures air quality by detecting gas concentrations, the LDR measures
light intensity, the PIR monitors silkworm activity, and the ultrasonic sensor detects insect
presence and movement.
- After processing the data, the ESP32 transmits the information to the Blynk cloud
platform over Wi-Fi. This allows for real-time monitoring and data logging, with users visualizing
and managing the data remotely via the Blynk mobile app. Instant notifications and updates
enable proactive adjustments to the environment as needed.
- This setup integrates hardware and software seamlessly, offering an efficient solution
for environmental monitoring. Leveraging the ESP32 and the connected sensors, the system
provides comprehensive insights and control, optimizing conditions for silkworm growth.


## Functional Block Diagram

![Refernce Circuit](https://github.com/athulp1/SILKWORM-GROWTH-MONITORING-SYSTEM/blob/main/BD.png)

Above image showcases the IoT-based silkworm growth monitoring system, employing an ESP32
microcontroller to collect data from various sensors. These sensors include DHT11 for temperature
and humidity, ultrasonic sensors for movement detection, PIR sensors for activity tracking, LDR
sensors for light intensity, and MQ135 sensor for air quality. Data is analyzed for fan and light
control, then seamlessly transmitted to Firebase Realtime Database Cloud, enabling user access
via web and mobile apps with periodic updates and alerts for timely intervention, enhancing
overall monitoring efficiency and user experience.


## Flowchart

![Refernce Circuit](https://github.com/athulp1/SILKWORM-GROWTH-MONITORING-SYSTEM/blob/main/flowchart.png)

- The flowchart illustrates the process of data collection and transmission in our project.
Starting with the ESP32 microcontroller, which serves as the central hub, data is gathered from
five sensors: MQ5 for air quality, DHT11 for temperature and humidity, LDR for light levels,
an ultrasonic sensor for detecting insect presence, and a PIR sensor for detecting silkworm motion.
- Each sensor provides specific environmental data: MQ5 measures air quality, DHT11
monitors temperature and humidity, LDR gauges light intensity, the ultrasonic sensor detects
insect presence through distance measurement, and the PIR sensor monitors silkworm movement.
- These sensor readings are then communicated to the Serial Monitor for real-time observation and debugging if needed. Simultaneously, the data is transmitted to Blynk Cloud for
secure storage and further analysis.
- This flowchart showcases the seamless flow of data from sensors to the ESP32, and
then onwards to both the Serial Monitor and Blynk Cloud, ensuring efficient monitoring and
management of environmental conditions for optimal silkworm growth.

## Hardware Design
-	Connect Sensors to ESP32: - Plug in temperature, humidity, pollution, motion and light level sensors to the ESP32 board and connect it to them
- Write Code to Read Data: - Using Arduino to tell ESP32 how to read information from each sensor
- Send Data to Cloud: - In your Arduino code, add instructions to send the recorded sensor data to your blynk cloud account
- Cloud Stores Your Data: - The blynk cloud will store your data in a safe digital space

![Refernce Circuit](https://github.com/athulp1/SILKWORM-GROWTH-MONITORING-SYSTEM/blob/main/FINAL.png)

## Arduino Code Setup

1. Install the Arduino IDE and required libraries.
2. Open the Arduino IDE and upload the provided SmartGlow_ESP8266.ino sketch to your NodeMCU ESP32.

## Results
The desired objective has been successfully achieved: the Sensor Hub's envisioned product now accurately presents temperature and humidity readings, as well as air quality (pollution) levels and light intensity. Moreover, all this valuable data is securely stored in the cloud, ensuring accessibility and reliability for users.

![Refernce Circuit](https://github.com/athulp1/SILKWORM-GROWTH-MONITORING-SYSTEM/blob/main/result.png)

## Contact
For any inquiries or issues, please contact Sunil Kanaki at athulpujari96@gmail.com









