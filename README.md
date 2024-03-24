# TickrMeterHack
Trying to reverse engineer the TickrMeter
The Firmware of the TickrMeter provides interesting functionalities but the battery level drainage is really annoying.
The battery barely makes a week with a few of refresh per hour. Forget the 3 weeks promised in the main page.

Starting to hack the TickrMeter ->https://tickrmeter.io/
Some info about the device I have:

- e-Ink screen: Something like the GDEM029E97 using SPI protocol (2.9 Inch Partial Refresh 296x128) -> https://www.aliexpress.us/item/32922467838.html?gatewayAdapt=glo2usa
- IoT board: ESP32-WROOM-32E
- HW revision: Pcb 1.6 2022.01.11

