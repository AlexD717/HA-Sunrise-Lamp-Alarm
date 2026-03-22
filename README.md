# HA-Sunrise-Lamp-Alarm

## Overview

### Description
This is an alarm clock that integrates with Home Assistant, and helps wake you up by gradually increasing the brightness of the light.

### Why I made this project
I made this project because I had a fairly old light alarm that I  liked and helped me wake up every day. However, it has no smart features and there is no way to configure a schedule (so that it doesn't run on the weekends) or create some cool light effects. This caused me to design my own that would integrate with Home Assistant, allowing me to easily control what days and time it runs, and even create some special effects.

### Pictures

![Final Render](assets/Render.png)

![Overall CAD](assets/CAD.png)

![Side View](assets/SideView.png)

![Top View](assets/TopView.png)

## Electrical

This project uses an SK6812 LED, generic keyboard button, and an XIAO ESP32 C3 microcontroller.

![Wiring Diagram](wiring/WiringDiagram.png)
https://wokwi.com/projects/458952556724127745

Connect 5v from the barrel jack to the 5v port of the ESP and the light strip

Connect GND from the barrel jack to the GND port of the ESP, the light strip, and one of the button pins

Connect the pin D10 (GPIO 10) to the light strip

Connect the pin D2 (GPIO 4) to the button

## BOM

See the material list here: [BOM](./Sunrise%20Lamp%20Alarm%20BOM.csv)