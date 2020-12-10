# ESP32 thing LED lights
SparkFun ESP32 Thing remote controlled lights

This repo is a instruction manual on how to use the Sparkfun ESP32 Thing to control LED Light strip. The advantage of using the ESP32 Thing is that you have access to both WiFi for remote control and Bluetooth (BT 4.0) for local control.

### Why the SparkFun ESP32 Thing?
Sparkfun has made it very easy to use the ESP32 from out of the box. One of the biggest painpoints when developing with the ESP32 is the need for a programmer and to handle the power surger carefully. The ESP32 Thing board takes care of everything so you can focus on programming.  Best yet it has I/O to plug a LiPo battery for when you are done with your sktech or you can power it through USB.

**My Favorite Features of this board**
- 3 SPI interfaces
- 3 UART interfaces
- Two I2C interfaces
- 2 digital-to-analog converters (DAC)
- Two I2S interfaces
- Power 2.2V - 3.6V / direct to usb 5V
- Wifi 802.11 b/g/e/o
- WPA/WAP2
- Bluetooth 4.2 / BLE
- on board Temperature Sensor
- on board HAll Sensor
- 520kB internal SRAM
- 4MB external flash
- Dual-core 32 bit

## Bill of Materials

### Hardware
- [Sparkfun ESP32 Thing](https://www.sparkfun.com/products/13907) 
- 5V LED Strip 
- Micro USB B Cable


### Software
- [Arduino IDE ](https://www.arduino.cc/en/main/OldSoftwareReleases)
- FTI Drivers (USB-to-serial converter) 

**For Windows**
```
https://learn.sparkfun.com/tutorials/how-to-install-ftdi-drivers/windows---quick-and-easy
```
**For Mac**

```
https://learn.sparkfun.com/tutorials/how-to-install-ftdi-drivers/mac
```

- Add theESP32 to the Arduino IDE Boards Manager

```
https://dl.espressif.com/dl/package_esp32_index.json
```

or 

- Install the ESP32 Core (Advance) - Espressif's official ESP32 Arduino core

```
git clone https://github.com/espressif/arduino-esp32.git esp32

```

- *(Optional)* BLE Scanner App --> I recommend [nRF Connect](https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp&hl=en&gl=US) from Nordic available for both iOS and android

### Setting up the ESP32

1. Set baud rate to **115200**.


## Recomended Reading
If you are unfamiliar with the ESP32 Thing here is a quick [101 document](https://learn.sparkfun.com/tutorials/esp32-thing-hookup-guide?_ga=2.19632440.1457604202.1607582738-1417300552.1602749477) on it.
