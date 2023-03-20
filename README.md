<h1>ESP32 Web Server with WiFi and ADC</h1>
<h2>Description</h2>
This is a simple example that demonstrates how to create GET and POST handlers for the web server on ESP32 using the ESP-IDF framework. The example contains code to create a Wi-Fi softAP, an HTTP server, and ADC read value.

<h2>Prerequisites</h2>
ESP32 development board
ESP-IDF v4.3 or later

<h2>Setup</h2>
Clone this repository or copy the code from main.c file.
Configure the Wi-Fi SSID and password in menuconfig.
Compile and flash the code to your ESP32 development board.

<h2>Usage</h2>
Connect to the Wi-Fi network created by the ESP32.
Open a web browser and enter the IP address of the ESP32 in the address bar.
The web page will display the current ADC reading and a slider to change the ADC value.
Change the slider position and click on the "Set Value" button to update the ADC reading.

<h2>License</h2>
This code is licensed under the MIT License. See the LICENSE file for details.




