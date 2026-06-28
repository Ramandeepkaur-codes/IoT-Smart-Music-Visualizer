# IoT-Smart-Music-Visualizer
An ESP32-based Smart Music Visualizer built using Wokwi. The project simulates sound levels using a potentiometer and visualizes them with a NeoPixel Ring while displaying the current sound intensity on a 20x4 I2C LCD.

## Overview

The Smart Music Visualizer is an ESP32-based IoT project that simulates sound intensity using a potentiometer and displays the sound level through a NeoPixel Ring and a 20x4 I2C LCD. The project was developed and tested using the Wokwi Simulator.

---

## Features

* Real-time sound level monitoring
* NeoPixel Ring color visualization
* LCD display for sound intensity
* ESP32 microcontroller
* Easy to simulate in Wokwi

---

## Components Used

* ESP32 DevKit V1
* NeoPixel Ring (WS2812)
* LCD 20x4 (I2C)
* Potentiometer


---

## Circuit Connections

### NeoPixel Ring

* VCC → 5V
* GND → GND
* DIN → GPIO 5

### LCD 20x4

* SDA → GPIO 21
* SCL → GPIO 22
* VCC → 5V
* GND → GND

### Potentiometer

* Left Pin → GND
* Middle Pin → GPIO 34
* Right Pin → 3.3V

---

## Technologies Used

* ESP32
* C++
* Wokwi Simulator
* NeoPixel Library
* LiquidCrystal_I2C Library

---

## Future Improvements

* Replace the potentiometer with a real microphone sensor.
* Integrate Blynk or ThingSpeak for cloud monitoring.
* Add Bluetooth control.
* Create multiple LED visualization modes.
* Display live sound graphs.

---

## Author

Ramandeep Kaur


