Smart Grain Guardian – Real-Time Grain Monitoring System
The Smart Grain Guardian is a cost-effective, scalable food storage monitoring system that uses environmental sensors, IoT connectivity, and GSM alerts to prevent grain spoilage. This project aims to revolutionize grain preservation practices by offering real-time insights, automated alerts, and remote access to critical data.

Project Overview
Designed to monitor grain storage facilities, this system continuously tracks temperature, humidity, gas emissions, and light exposure. When thresholds are breached, it sends SMS notifications to stakeholders and stores sensor data for later analysis via IoT platforms.
- Continuous monitoring of environmental conditions
- Early detection of spoilage indicators
- GSM-based alert system for immediate notification
- Energy-efficient operation
- Scalable design for all facility sizes
- Seamless integration with IoT platforms
- Support materials for training and deployment
- Contribution to reducing post-harvest losses and improving food security

System Architecture
Hardware Components
| Component             | Purpose                                                   |
|----------------------|-----------------------------------------------------------|
| Arduino UNO          | Central processing and sensor management                  |
| DHT22 Sensor         | Measures temperature and humidity                         |
| MQ135 Gas Sensor     | Detects gases like CO2, alcohol, and ammonia              |
| LDR or Light Sensor  | Detects light exposure and intensity                      |
| GSM SIM900 Module    | Sends SMS alerts to registered numbers                    |
| ESP8266 Wi-Fi Module | Transmits sensor data to IoT platforms                    |
| LCD Display          | Shows sensor readings in real time                        |
| Buzzer               | Activates when thresholds are crossed                     |
| Power Supply         | Ensures uninterrupted power with backup options           |
| Enclosure            | Protects the system from dust and physical damage         |

Software Requirements
- Arduino IDE with necessary libraries: DHT, GSM, ESP8266 WiFi
- MQTT or HTTP protocols for IoT communication
- Serial communication setup for testing
- Data logging mechanisms for historical tracking
- Alert logic implementation based on thresholds
- Mobile number configuration for SMS delivery

Functional Modules
- Data Collection Module: Gathers temperature, humidity, gas, and light data
- Preprocessing Module: Cleans, formats, and scales the incoming data
- Feature Selection Module: Selects critical indicators for spoilage detection
- Alerting Module: Sends notifications when thresholds are breached
- Monitoring & Evaluation Module: Logs performance and enables system diagnostics

Key Features
- Threshold-based real-time monitoring
- GSM-powered alert notification system
- LCD and buzzer feedback for local awareness
- Reliable sensor fusion using Arduino platform
- Modular and low-cost implementation
- Suitable for small to large grain facilities

Future Scope
- Mobile application and centralized web dashboard
- GPS-enabled alerts for location tagging
- Advanced predictive analytics via cloud integration
- Solar-based power solutions for remote deployment
- Machine learning integration for dynamic alert logic
- Community training and agricultural partnerships

Testing and Results
- Accurate detection and responsive alerting tested in controlled environments
- Decision Tree Regression used for spoilage prediction modeling
- Sensor reliability validated across multiple cycles
- Performance enhanced by data logging and trend analysis

References
Refer to the technical documentation and literature survey within the repository for related studies, IEEE research, and IoT architecture.

Getting Started
1. Connect sensors to Arduino UNO using the schematic
2. Upload firmware using Arduino IDE
3. Insert and configure GSM SIM with a valid phone number
4. Observe LCD readings and receive alerts when spoilage risk is detected

Contributing
Contributions to improve system reliability, dashboard design, or IoT functionality are welcome. Please open an issue or pull request for review.

