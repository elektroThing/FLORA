# FLORA - Garden Monitoring System
![](./images/FLORA.png)

FLORA is an open-sourced ESP-32-based project that is a garden monitoring system powered by solar energy to help make your fingers just a little greener! :) The board is equipped with sensors to measure environmental temperature and humidity as well as connect to several soil moisture sensors to accurately measure up the moisture levels of the ground. It also boasts a LoRa transceiver that allows it to communicate over 3 miles (5 kilometers) and using the ESP-NOW protocol, the ability to communicate to other ESP-32 devices up to 400 meters away. 

# What is it

FLORA is a long-range ESP-32-based garden weather station with some unique tricks. First, it has a LoRa module that allows it to be used across a considerable distance (up to around 2 miles/ 3 km). This makes it suited for use in a more extensive garden or an allotment within walking distance. On top of that, it also has a companion soil moisture sensor that can measure the moisture left in the top layer of the soil. This is particularly useful to inform you if it has had some rain locally in the area recently and to prevent unnecessary waste of precious water. The system is powered by a coin cell battery that gets recharged by a solar panel.

Building on my [Plant-Bot](https://github.com/elektroThing/Plant-Bot) project, I was inspired to make a version that is a little more suited for the outdoors and looking after multiple plants.

Key Features;
* 


## Use case


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
