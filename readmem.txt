Bitcoin Price Checker

A fun project using the ESP32 to fetch Bitcoin prices and display price trends with an LED. Powered by the CoinGecko API, this project lets you track price changes visually, making it a cool tool for crypto enthusiasts! 🚀

Features

Real-Time Bitcoin Price Tracking: Fetches the current price of Bitcoin in USD.

Feedback:

Price Increase

Price Stable

Price Drop

Error Handling:

Blinking LED when WiFi is disconnected or HTTP requests fail.

How It Works

Connect the ESP32 to WiFi.

Fetch Bitcoin prices every ~60 seconds from the CoinGecko API.

Compare the latest price with the previous price.

Components

ESP32 board

USB cable (for programming the ESP32)

Setup Instructions

Install the Arduino IDE if not already installed.

Add the ESP32 board to the Arduino IDE:

Go to File > Preferences.

Add this URL to "Additional Board Manager URLs": https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json.

Go to Tools > Board > Board Manager, search for esp32, and install the ESP32 library.

Clone this repository or copy the code to your Arduino IDE.

Replace ssid and password in the code with your WiFi credentials.

Upload the code to your ESP32.

API Used

CoinGecko API

Example Output

Serial Monitor

WiFi connected!
IP Address: 192.168.1.100
Sending HTTP GET request...
HTTP Response Code: 200
API Response: {"bitcoin":{"usd":97284.65}}
Parsed Price: 97284.65
Price Increased!

Known Issues

Ensure the WiFi credentials are correct.

Sometimes API responses might take longer; increase the delay if necessary.

Future Improvements

Add support for multiple cryptocurrencies.

Display price trends on an OLED or LCD screen.

Feel free to contribute or raise issues!
