# Dragon Board 410c Windows 10 IoT Core with Seeed Grove Starter Kit sample
Dragon Board 410c Windows 10 IoT Core with Seeed Grove Starter Kit sample

<b>***This is not a working sample yet. It was forked from another depository for another mezzanine card. Work in progress.***</b>

This repository contains sample UWP application for DragonBoard 410c and sensors with Seeed Grove card. Unlike other samples, this application connects many sensors listed below to demonstrate how to utilize multiple sensors. The application uses onboard LEDs and GPS.

### DragonBoard 410c 
<img src="https://www.96boards.org/product/ce/dragonboard410c/images/DragonBoard-UpdatedImages-front.png" width="200">

Click [here](https://www.96boards.org/product/dragonboard410c) for more detail.

### Seeed Grove card starter kit for 96board
<img src="https://statics3.seeedstudio.com/images/product/110060157%201.jpg" width="200">

Click [here](http://linksprite.com/wiki/index.php5?title=Linker_Mezzanine_card_starter_kit_for_96board) for more detail.

### DragonBoard 410c Pin and Grove card diagram schematics
<p>
<a href="https://github.com/96boards/96boards-sensors/raw/master/Sensors.pdf">Schematics link(pdf)</a>
</p>

From the diagram, you can see pin number for each Degital Interface
- D1 -> 36
- D2 -> 13
- D3 -> 115
- D4 -> 24

## How to install Windows 10 IoT Core for DragonBoard
Follow the instruction [here](https://developer.microsoft.com/en-us/windows/iot/getstarted)

## Device Setup
In this sample, plug sensors as below.

- Touch Sensor -> D1
- LED -> D2
- Button -> D3
- Tilt Sensor -> D4
- TPM36 -> ADC1
- Photoresistor -> ADC2

## Sensors 
#### Output
- LED: Red LED and two onboard Green LEDs

#### Input: Switch
- Touch sensor: When you touch the sensor, it lights up LEDs and get data from sensors.
- Button: When you push the button, it lights up LEDs and get data from sensors.
- Tilt Module: When you tilt the module one way, it lights up LEDs and get data from sensors.

#### Input: Sensor
- TPM36: Measure temperature
- Photoresistor: Measuare the brightness
- Onboard GPS: Measure location

## Lisence
MIT
