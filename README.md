# Grade 8 Projects

## Activities Overview

In this repository, you'll find several IoT-based projects for Grade 6 students. Each project involves using ESP32 and other hardware components to control devices, collect data, and send the data to **Adafruit IO**, a cloud platform.

### Activities:

- **ESP_Servo**: Control servo motors using ESP32.
- **LED**: Simple LED control.
- **LED_IoT**: Control LEDs remotely over the internet using Adafruit IO.
- **Moisture Based Watering**: Automate watering based on soil moisture readings.
- **Moisture**: Measure soil moisture with an analog sensor.
- **Motor_Speed_IoT**: Control motor speed via the internet.
- **Relay**: Control a relay connected to a device like a pump or motor.
- **Relay_IoT**: Control a relay remotely via Adafruit IO.
- **Smart_Plant_Monitor_IoT**: Build a smart plant monitoring system that tracks soil moisture and activates watering when necessary.
- **Smart_Water_Tank**: Monitor water tank levels and trigger alerts or actions.
- **SoilMoisture_IoT**: Monitor soil moisture levels and send the data to Adafruit IO.
- **Ultrasonic**: Measure distance using an ultrasonic sensor and send the data to Adafruit IO.
- **Ultrasonic_IoT**: Control or monitor distance measurement using an ultrasonic sensor via Adafruit IO.

---

## Setup Instructions

### 1. **Adafruit IO Setup**:

For all IoT projects, you need an **Adafruit IO** account to interact with the cloud. To set up the projects:

1. **Create an account on Adafruit IO**: Go to [Adafruit IO](https://io.adafruit.com/) and sign up for a free account.
2. **Create Feeds**: For each project, create a feed in Adafruit IO. You’ll need a feed to store or send data like moisture levels, servo positions, etc.
   - For example, for the **SoilMoisture_IoT** project, create a feed named `soil_moisture`.

### 2. **WiFi and Adafruit IO Credentials**:

Replace the placeholders `"your_username"`, `"your_aio_key"`, `"your_wifi_ssid"`, and `"your_wifi_password"` in the project code files with your actual Adafruit IO and WiFi credentials.

- **IO Username**: The username you created on Adafruit IO.
- **IO Key**: This is your Adafruit IO key that can be found in your Adafruit IO dashboard under **My Profile**.
- **Wi-Fi SSID**: Your Wi-Fi network name.
- **Wi-Fi Password**: Your Wi-Fi password.

Example:

```cpp
#define IO_USERNAME  "your_username"      // Replace with your Adafruit IO username
#define IO_KEY       "your_aio_key"       // Replace with your Adafruit IO key
#define WIFI_SSID    "your_wifi_ssid"     // Replace with your Wi-Fi SSID
#define WIFI_PASS    "your_wifi_password" // Replace with your Wi-Fi password
