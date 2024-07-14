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

![Refernce Circuit]()








