# Home Assistant config

## Overview page

Using lovelace ui.

![Overview][./images/screen.png]

## Hardware

For Sonoff/Tuya devices default software has been flashed with Tasmota.

- [Sonoff Basic](https://sonoff.itead.cc/en/products/sonoff/sonoff-basic)
- [Sonoff Pow R2](https://sonoff.itead.cc/en/products/sonoff/sonoff-pow-r2)
- [Sonoff Socket S20](https://sonoff.itead.cc/en/products/residential/s20-socket)
- [Sonoff RF Bridge 433](https://sonoff.itead.cc/en/products/appliances/sonoff-rf-bridge-433)
- [Sonoff Slampher E27](https://sonoff.itead.cc/en/products/residential/slampher-rf)
- [BlitzWolf BW-SHP2 WIFI Smart Socket EU Plug](https://www.aliexpress.com/item/BlitzWolf-BW-SHP2-WIFI-Smart-Socket-EU-Plug-220V-16A-Remote-Control-Smart-Timing-Switch-Work/32871562977.html) - with monitoring
- [Window/door sensors](https://www.aliexpress.com/item/Black-Wireless-GSM-PIR-Alarm-Monitor-Simple-Easy-Use-GSM-Home-Security-Alarm-System-PIR-Infrared/32585915880.html)
- [Water leak detector](https://www.aliexpress.com/item/Niwoolf-433MHz-Wireless-Water-Leakage-Detector-Water-Leak-Sensor-For-Our-433MHz-Home-Burglar-Wifi-GSM/32903148693.html)
- [Remote Control 433Mhz](https://sonoff.itead.cc/en/products/accessories/433-rf-controller)
- [Wireless-Infrared-PIR](https://www.aliexpress.com/item/DIGOO-DG-HOSA-Wireless-Infrared-PIR-Detector-Sensor-For-433MHz-Home-Security-Alarm-System-Kits/32819986075.html)
- LG TV
- Raspberry Pi 2/3 (one with camera)
- NodeMCU running custom temperature/humidity/pir sensors


## TODO

- ZigBee/Z-Wave - current devices mostly use Wifi or RF433 Mhz for communication.
- Configuration split into smaller chuncks [WIP]
- Move from RaspberryPI SD card to SSD(120 - 250GB), SD cards tend to wear out when under heavy small writes (worst case scenario would be SD card remains in read only mode).
- Wifi network mesh and expanding usage range(probably needs new hardware, AP x 2, router, switch)
- Separate MQTT broker from single RaspberryPi setup
- LoRa experiment (currently not needed)