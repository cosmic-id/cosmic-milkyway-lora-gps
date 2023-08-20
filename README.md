# Cosmic Milky Way

## Overview
Cosmic Milky Way is a bundled shield contains of LoRa Chip and GPS Chip. It helps you do rapid prototyping for LoRa Tracking application. 

The GPS Chip used is **Quectel GPS L86** while the LoRa Chip used is **RFM95W**.

### LoRa(WAN) Chip Interfacing

| Cosmic LoRa Ray   | RFM95W |  
|-------------------|------- |
| D11               | MOSI   |
| D12               | MISO   |
| D13               | SCK    |
| D10               | NSS    |
| D9                | RST    |
| D2                | DIO0   |
| D6                | DIO1   |

## GPS Chip Interfacing

The GPS RX, TX to microController TX, RX **must be selected by the headers** provided in the shield. 

> The provided examples below are based on the uC Tx = 4, and uC Rx = 3

## Prerequisite

- Install library [Software Serial](https://docs.arduino.cc/learn/built-in-libraries/software-serial)
- Install library [Tiny GPS](https://github.com/mikalhart/TinyGPSPlus)
- Install library LoRaWAN

## Example

> Please install the [prerequisite](#prerequisite) libraries before running the examples code

- [Unparsed NMEA GPS Data](NMEA-gps-data-unparsed/NMEA-gps-data-unparsed.ino)
- [Parsed Location GPS Data](location-date-time-parsed/location-date-time-parsed.ino)

## FAQ

On-going

## Contact Us

Any issue of the tutorial or need IoT solutions? Please [contact us](https://wa.me/6282117421332)