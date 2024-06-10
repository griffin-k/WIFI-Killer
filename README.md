# WIFI-Killer

## About this Project

This firmware allows you to easily perform a variety of actions to test 802.11 networks using an ESP8266. It's also a great project for learning about WiFi, microcontrollers, Arduino, hacking, and electronics/programming in general.

The deauthentication attack is the main feature, which can be used to disconnect devices from their WiFi network. Although this denial-of-service attack is nothing new, many devices are still vulnerable to it. Luckily, this is slowly changing with more WiFi 6 enabled devices being used. However, many outdated WiFi devices remain in place, such as in cheap IoT hardware. With an ESP8266 Deauther, you can easily test this attack on your 2.4GHz WiFi network/devices and see whether it's successful or not. If it is, you know you should upgrade your network.

## Disclaimer

This project is a proof of concept for testing and educational purposes only. It is not intended for any illegal activities.

Neither the ESP8266, nor its SDK was meant or built for such purposes. Bugs can occur!

**Use it only against your own networks and devices!**
Please check the legal regulations in your country before using it.
We don't take any responsibility for what you do with this program.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/griffin-k/WIFI-Killer
    ```

2. Download and install the ESP Flasher Application.

3. Navigate to the `NodeMcu flasher master` folder.

4. Select the appropriate version (32-bit or 64-bit) according to your Windows version.

5. Select the BIN file and upload it to your ESP8266.

## Usage

1. Power up your ESP8266 device with the firmware installed.

2. Connect to the ESP8266 WiFi network.

3. Open a web browser and navigate to the IP address of the ESP8266 (typically `192.168.4.1`).

4. Follow the instructions provided in the web interface to perform various actions, including the deauthentication attack and testing your WiFi network/devices.

5. For step by step Usage [visit](https://deauther.com/docs/category/usage/)

