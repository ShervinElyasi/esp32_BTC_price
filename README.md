# Bitcoin Price Tracker with ESP32 💡💸

### Description
This project fetches the current Bitcoin price from the CoinGecko API using your ESP32 and displays the price changes using serial.print() function. Whether the price goes up, down, or stays the same, your serial monitor will reflect the market vibe!

### Features
- Connects to WiFi and fetches Bitcoin price from CoinGecko.
- Compares the current price with the previous one.
- Configurable request intervals.

### Components
- ESP32 microcontroller
- Arduino IDE with ESP32 board support
- Wi-Fi network credentials (SSID and password)
- Internet connection for API requests

## Setup Instructions

1. **Install the Arduino IDE:**
   - Download and install the [Arduino IDE](https://www.arduino.cc/en/software).
   - Install the **ESP32 board support** by following the [ESP32 setup instructions](https://github.com/espressif/arduino-esp32).

2. **Clone the repository:**
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ShervinElyasi/esp32_BTC_price.git
3. **Upload the code:

    Open the project in Arduino IDE.
    Select the correct board and port for your ESP32.
    Upload the code to your ESP32.

4. **Configure Wi-Fi:

    In the setup() function, replace ssid and password with your Wi-Fi credentials.
    Upload the updated code to the ESP32.
