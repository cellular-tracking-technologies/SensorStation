# SensorStation

This repo contains the SensorStation schematics and CAD files. You can use this to assist with development, troubleshoot problems, or even create your own SensorStation.

If you are looking to purchased a fully assembled and tested SensorStation, complete with Raspberry Pi Compute module installed, visit: http://store.celltracktech.com/

# SensorStation Overview

The SensorStation is a powerful platform for transmitting and receiving information wirelessly, with multiple radio channels.

While its primary function is to collect data from wildlife telemetry devices, it can be used for any multi-channel wireless
application, including IoT, amateur radio, and building wireless networks.

The SensorStation offers the following features:

* Support for the Raspberry Pi Compute Module CM3+ (pre-programmed with SensorGnome if purchased from CTT)
* USB OTG switch allows for programming of Compute Module while directly connected to board
* GPS receiver with built in chip antenna, with RF switch for external antennas
* 5 radio channels with SMA connectors featuring the HopeRF footprint, making it compatible with VHF and UHF systems, such as LoRa or FSK, from 142-1000MHz and 2.4GHz
* Each radio is controlled by a dedicated Atmel AVR 32U4, featuring the Arduino bootloader, hardwired to the USB network
* Raspberry Pi compatible header for connecting accessories, such as the InkyPhat eInk screen and more
* 4 directional buttons
* 2 status indication LEDs controlled by GPIO
* 3 I2C accessory ports, with dedicated GPIO per port
* Multi-channel ADC, for measuring system voltages, temperature, light levels, battery voltage, solar voltage, and additional channels broken out
* DS3231 real time clock with extreme accuracy along with coin cell slot
* Composite video output
* Wide range DC power input from 8-24VDC
* 6 USB 2.0 ports, each with dedicated transaction translator, typically used for Software Defined Radio (SDR)
* SIM800C quad band GSM modem
* eSIM (SIM on chip), soldered on if purchased from CTT (requires data plan)

# SensorStation Acessories

Also available for a variety of SensorStation accessories. You can even build your own. Check our our SensorStation Acessory Template to learn more.

![SensorStation](https://github.com/cellular-tracking-technologies/SensorStation/blob/master/SensorStationCurrent1.png?raw=true)
