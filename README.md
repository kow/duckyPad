# duckypad: Scriptable Mechanical Keypad with RGB Backlight

![Alt text](resources/pics/title.jpg)

duckypad is a mechanical keypad with RGB backlight, OLED screen, and 15 keys. Each key can execute a script when pressed.

The scripts can be as simple as shortcuts like `ctrl+c`, or as complex as [creating root backdoors](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payload---OSX-Root-Backdoor) or [grabbing passwords](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payload---download-mimikatz%2C-grab-passwords-and-email-them-via-gmail). It's all customizable by you.

Multiple profiles are supported, for different programs/environments.

## Features

* 15 mechanical switches
* Individually addressable RGB backlights with animations
* OLED screen displaying current profile and key functions
* SD card script storage
* Standard duckyscript parsed onboard
* Multiple profiles
* USB-C connector

## Video

Here's a silly video showing duckypad in action, as well as the timelapse of me building it.

https://www.youtube.com/watch?v=EGLLCtRuEuM

## Getting started

Please see [this guide](./getting_started.md) on how to use your duckypad.

## Making one yourself

Please see [this guide](./build_it_yourself.md).

## Questions?

Feel free to ask in the issue section, or email me at `dekunukem__gmail__com`.

## kowmod1 ##

![Alt text](resources/pics/kowmod1.jpg)

replaced LCD with cheaper 4 pin version, uses any ~$3 128x64 oled LCD with VCC,GND,SCL,SDA pinout order (https://www.ebay.ca/itm/0-96-I2C-IIC-SPI-Serial-128X64-White-OLED-LCD-LED-Display-Module-for-Arduino-LR/392728983410)
replaced sk6812 mini with ws2812b mini, added gerber, bom, and cpl for jlcpcb assembly