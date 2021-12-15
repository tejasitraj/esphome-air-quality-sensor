# esphome-air-quality-sensor
My implementation of an Air Quality Sensor based on a PMS5003, DHT11 and ESP32. 

![IMG-20211210-WA0000](https://user-images.githubusercontent.com/14822776/146227121-e74ced0b-9e5a-4cfd-8767-d360785260e4.jpg)

This implementation is based on [a guide](https://www.pieterbrinkman.com/2021/02/03/build-a-cheap-air-quality-meter-using-esphome-home-assistant-and-a-particulate-matter-sensor/) by Pieter Brinkmann. Follow that guide for step by step instructions.

# Shopping List

- [ESP32](https://www.banggood.com/Geekcreit-ESP32-WiFi+bluetooth-Development-Board-Ultra-Low-Power-Consumption-Dual-Cores-Pins-Unsoldered-p-1214159.html?cur_warehouse=CN&rmmds=search)
- [PMS5003 Sensor](https://www.banggood.com/PMS5003-PM2_5-Air-Particle-Dust-Sensor-Laser-Digital-Output-Module-High-Precision-Air-Haze-Detection-Smart-Home-Device-p-1553818.html?cur_warehouse=CN&rmmds=search)
- [DHT11](https://www.banggood.com/10pcs-KY-015-DHT11-Temperature-Humidity-Sensor-Module-p-1338053.html?cur_warehouse=CN&rmmds=search)
- [Cheap box to house everything](https://www.banggood.com/100-x-80-x-32mm-DIY-Electronic-Plastic-Housing-Junction-Box-Power-Supply-Box-Instrument-Case-Jig-Box-p-1183119.html?rmmds=myorder&cur_warehouse=CN)
- Micro USB Power Supply

# Connections

| PMS5003 Pin|ESP32 Pin|
| ---------- | ------- |
| 1 | VIN |
| 2 | GND |
| 3 | GPIO14 |
| 4 | GPIO26 |
| 5 | GPIO27 |

| DHT 11 Pin | ESP32 Pin |
| ---------- | --------- |
| GND | GND |
| VCC | 3V3 |
| DATA | GPIO18 |
