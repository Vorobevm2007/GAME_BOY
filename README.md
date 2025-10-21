# **<h1 align="center">Game Boy</h1>**

<p align="center"><img src="Image/Photo The Game Boy.jpg" style="border: 20px solid black; width="640" height="480"></p>

## The preface

### Here I will tell you step by step how to make a "GAME BOY". You can use this project as the basis of your project, which you can further improve and develop.

## **<h1 align="center">Table of contents</h1>**

# [Assembling](#Assembling)

- Nano Type-C
- Joystick Module
- OLED display 0.96 I2C 128x64

# [Programming](#Programming)

- Installing the library for the display (OLED display 0.96 I2C 128x64)
- Installing the library for the joystick (Joystick Module)

# [Where can I buy it?](#WhereCanIBuyIt)

- Purchase on Wildberries Nano Type-C
- Purchase on Wildberries OLED display 0.96 I2C 128x64
- Purchase on Wildberries Joystick Module

## **<h1 align="center">Game Boy</h1>**

## [Assembling](#Assembling)

### Nano Type-C

<p align="left"><img src="Image/Scheme Ardiuno NANO.png" style="border: 5px solid black; width="238" height="94"></p>

I specially selected an **Arduino Type-C** board for this project. In the future, if you want to make a case for it, *you can *tarnish* the **GAME BOY** with a phone and Type-C wires on Type-C*.

### Joystick Module

<p align="left"><img src="Image/Scheme keyes_Sjoys.png" style="border: 5px solid black; width="240" height="100"></p>

**Connection**

<p align="left"><img src="Image/Arduino Nano in Sjoys.jpg" style="border: 5px solid black; width="960" height="400"></p>

| Joystick Module | Nano Type-C |
| --------------- | ----------- |
| GND | GND |
| VCC | 3V3 |
| VRX | A1 |
| VRY | A0 |
| SW | A2 |

### OLED display 0.96 I2C 128x64

<p align="left"><img src="Image/Scheme OLED I2C.png" style="border: 5px solid black; width="240" height="150"></p>

**Connection**

<p align="left"><img src="Image/Arduino Nano in OLED.jpg" style="border: 5px solid black; width="960" height="400"></p>

| OLED display 0.96 I2C 128x64 | Nano Type-C |
| ---------------------------- | ----------- |
| GND | GND |
| VCC | 5V |
| SCL | A5 |
| SDA | A4 |

## [Programming](#Programming)

Unfortunately, I have no C programming experience. I tried to write the most understandable code with comments. If you have any comments about the code, please email me. I will be glad to listen to your opinion.

### Installing the library for the display (OLED display 0.96 I2C 128x64)

There are some minor problems with installing the library for the OLED display. This library is not listed in Library Management. You need to download it from [GitHub](https://github.com/jlegas/OLED_I2C). And upload it to the Arduino IDE (Sketch --> Connect the library --> Add .ZIP library...).

### Installing the library for the joystick (Joystick Module)

You can install this library in the editor itself.

<p align="left"><img src="Image/the name of the library for the joystick.jpg" style="border: 5px solid black; width="960" height="300"></p>

## [Where can I buy it?](#WhereCanIBuyIt)

*Personally, I bought all the boards on Wildberries. And so the links will be from "Wildberries".*

### Links:

* [Purchase on Wildberries Nano Type-C](https://www.wildberries.by/catalog/193661767/detail.aspx)
* [Purchase on Wildberries OLED display 0.96 I2C 128x64](https://www.wildberries.by/catalog/119492177/detail.aspx)
* [Purchase on Wildberries Joystick Module](https://www.wildberries.by/catalog/170400911/detail.aspx)

## Enjoy using it ;)
