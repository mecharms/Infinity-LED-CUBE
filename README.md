# Infinity-LED-CUBE


The CUBE is heavily inspired by Hypercube made by **The Hyperspace Lighting Company**: [Hyperspace Cube](https://hyperspacelight.com/products/hypercube10)

### Here you can find video of the building process: [Youtube](https://www.youtube.com/watch?v=Ci29R1Xrb-4)
![LED!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/ma.jpg)


## Hardware:
  - ESP32 - I recommend ,,original board" as I had a lot of troubleshooting with cheap clone.
   - Screen OLED 0,96 Arduino I2C SSD1306 128x64px
   - KY-040 Rotary Encoder
   - Leds: WS2812B - 4.8m (144 leds)
   - 5V 5A Power supply
- The mechanical structure is 3D printed - files in the folder
- 24 x M2 15mm wood screws
- 6 x 210mmx210mm/4mm one-way tempered mirrors 
![cube!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/cube_model.PNG)
![cube2!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/cube_model2.PNG)
![e1!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/enclosure1.PNG)
![e2!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/enclosure2.PNG)
![e3!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/enclosure3.PNG)
## Electrical connection
Here is the electrical connection scheme for controller (patterns selector) : 

![scheme4!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/scheme4.png)

![scheme1!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/cube-scheme1.jpg)
![scheme2!](https://github.com/mecharms/Infinity-LED-CUBE/blob/main/photos/cube-scheme2.jpg)
## Code

Libliaries I used: 
- [Arduino](https://github.com/arduino/ArduinoCore-avr/blob/master/cores/arduino/Arduino.h)
- [FastLED](https://github.com/FastLED/FastLED)
- [Wire](https://www.arduino.cc/reference/en/language/functions/communication/wire/)
- [Adafruit_SSD1306](https://github.com/adafruit/Adafruit_SSD1306)
- [Adafruit-GFX-Library](https://github.com/adafruit/Adafruit-GFX-Library)
- [FreeSans9pt7b](https://github.com/adafruit/Adafruit-GFX-Library/blob/master/Fonts/FreeSans9pt7b.h)
- [RotaryEncoder](https://github.com/mathertel/RotaryEncoder)
- [OneButton](https://github.com/mathertel/OneButton)
## Links

- [FastLED](https://fastled.io/)
- [FastLED reddit](https://www.reddit.com/r/FastLED/)
