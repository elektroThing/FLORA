# FLORA - Garden Monitoring System
![](./images/FLORA.png)

FLORA is an open-sourced ESP-32-based project that is a garden monitoring system powered by solar energy to help make your fingers just a little greener! :) The board is equipped with sensors to measure environmental temperature and humidity as well as connect to several soil moisture sensors to accurately measure up the moisture levels of the ground. It also boasts a LoRa transceiver that allows it to communicate over 3 miles (5 kilometers) and using the ESP-NOW protocol, the ability to communicate to other ESP-32 devices up to 400 meters away. 

# What is it

FLORA is a long-range ESP-32-based garden weather station with some unique tricks. First, it has a LoRa module that allows it to be used across a considerable distance (up to around 2 miles/ 3 km). This makes it suited for use in a more extensive garden or an allotment within walking distance. On top of that, it also has a companion soil moisture sensor that can measure the moisture left in the top layer of the soil. This is particularly useful to inform you if it has had some rain locally in the area recently and to prevent unnecessary waste of precious water. The system is powered by a coin cell battery that gets recharged by a solar panel.

Building on my [Plant-Bot](https://github.com/elektroThing/Plant-Bot) project, I was inspired to make a version that is a little more suited for the outdoors and looking after multiple plants.

Key Features;
* Compatible with two energy long-range protocols - LoRa and ESP-NOW
* Can we powered solely with a single solar panel
* Soil Moisture  sensing
* Temperature and Humidity sensing
* Easily programmable - USB
* WiFi and Bluetooth Enabled

## Use case | Garden Monitoring System
FLORA's main use case is to make your garden or greenhouse just that little bit smarter. It has an onboard sensor that can be used to measure temperature and humidity, three ports to connect to a soil moisture sensor, and a LoRa module that can be used to transmit data to any other LoRa modules that are on the same frequency band up to 3 miles away.

The goal of this is to ensure more efficient use of resource by generating useful insights to the user as to what the soil moisture levels are like and if the ambient environment is condusive for the particular crop or plant that is being grown. This should hopefully make gardening and home farms more convinient and resistant to our ever changing climate.

This module fits in a simple

## Specification

* Microcontroller | [ESP32-WROOM-32E](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf)
    * WiFi | 802.11b/g/n
    * Bluetooth | BLE 4.2
    * FLASH | 8MB
    * Programming | USB over UART (CP2102)
* Environment Sensor | [SHT20](https://sensirion.com/products/catalog/SHT20/)
    * Temperature Accuracy | to within 0.3 °C
    * Humidity Accuracy | to within 3%RH
    * Interface | I²C
* Soil Moisture Sensor | Made by elektroThing
    * Uses Capacitive Sensing
* LoRa Transceiver | [RA-01H](https://cdn.ozdisan.com/ETicaret_Dosya/632831_134737.pdf)
    * Frequency | 803/930 MHz
    * Interface | SPI 
* Power | 700mA 3.3V LDO or 1A 3.3V SMPS
* Mounting | Hammond Case with 2x M.2. Holes

## License

MIT License

Copyright (c) 2022 elektroThing

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
