# Medibox - Intelligent Medication Management System

## Project Overview
Medibox is an IoT-enabled smart medication management system that combines embedded hardware with cloud-based monitoring to ensure optimal medication storage conditions and timely dosage reminders.

## Key Features
### Core Functionality
- Configurable multi-alarm medication reminder system
- Precision timekeeping with NTP synchronization
- Dual interface (physical controls + web dashboard)
- Audible and visual alert systems

### Environmental Monitoring
- Continuous temperature and humidity tracking
- Ambient light intensity measurement
- Threshold-based condition alerts

### Adaptive Control
- Automated shading mechanism
- Medication-specific parameter presets
- Real-time data visualization

## Technical Specifications
### Hardware Components
| Component | Specification | Purpose |
|-----------|--------------|---------|
| Microcontroller | ESP32 DevKit-C | Central processing unit |
| Environmental Sensor | DHT22 | Temperature/humidity monitoring |
| Light Sensor | LDR | Ambient light measurement |
| Actuator | SG90 Servo | Shading mechanism control |
| Display | SSD1306 OLED | User interface |

### Software Stack
| Layer | Technology | Purpose |
|-------|------------|---------|
| Firmware | Arduino C++ | Device control logic |
| Communication | MQTT | Data transport protocol |
| Dashboard | Node-RED | Visualization interface |

## System Architecture
