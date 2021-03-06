---
layout: page
title: Electronics
permalink: /electronics/
---

## Snaptics Electronics Overview

The Snaptics control board is an expansion board for a Sparkfun ESP32 Microcontroller to allow the ESP32 to safely and simply control the electronics used in various Snaptics actuation modules. For information on the ESP32 microcontroller please visit their product page [here](https://www.sparkfun.com/products/13907).

<p align="center">
  <img src="photos/../../photos/electronics/PCBV2_diagram.png" alt="snaptics" width="400"/>
</p>

The Snaptics PCB board provides mounting pins to attach to a [Sparkfun ESP32 Development Board](https://www.sparkfun.com/products/13907). With the ESP32 as the controller this board allows makers to control up to 8 vibration motors using the ERM output pins and 8 servo motors using the Servo output pins at a time. Servo output pins connect directly into the ESP32 PWM output pins and to motor power while ERM output pins are controlled with a simple onboard MOSFET circuit to simplify the control on the microcontroller. The control board is powered with 6V operating power pack to provide power to the actuation modules. ESP32 power is provided directly to the board using a separate power supply of operating range 2.2V to 3.6V. 

## How to Get a Snaptics Control Board - Under Construction
We are still working on production and distribution of our electronics board. Please check back here at a later date!

<!-- All documentation and files required for the reproduction of these electronics board are provided below. We recommend outsourcing these boards for production and turnkey assembly to make the process as simple and cheap as possible. While there are many suppliers for PCB manufacture, we have used PCBWay and can confirm the PCBs work. For more detailed instructions on how to obtain your own Snaptics control board please visit our associated [tutorial](www.snaptics.org/tutorials).

|**Board Version**|**Description**|**Downloads**|
|:-----:|:-----|:-----:|
| V2.0 | Basic ESP32 expansion board | Gerber | -->


## Pin Assignments

### ERM Output Pins

|**Output Pin <br> Location**|**Associated <br> ESP32 Pin**|
|:-----:|:-----:|
|<img src="../photos/electronics/ERMPinA.png" alt="stretch_module" style="height:50px;">| 34 |
|<img src="../photos/electronics/ERMPinB.png" alt="stretch_module" style="height:50px;">| 35 |
|<img src="../photos/electronics/ERMPinC.png" alt="stretch_module" style="height:50px;">| 25 |
|<img src="../photos/electronics/ERMPinD.png" alt="stretch_module" style="height:50px;">| 26 |
|<img src="../photos/electronics/ERMPinE.png" alt="stretch_module" style="height:50px;">| 27 |
|<img src="../photos/electronics/ERMPinF.png" alt="stretch_module" style="height:50px;">| 14 |
|<img src="../photos/electronics/ERMPinG.png" alt="stretch_module" style="height:50px;">| 12 |
|<img src="../photos/electronics/ERMPinH.png" alt="stretch_module" style="height:50px;">| 13 |

### Servo Output Pins

|**Output Pin <br> Location**|**Associated <br> ESP32 Pin**|
|:-----:|:-----:|
|<img src="../photos/electronics/ServoPinA.png" alt="stretch_module" style="height:100px;">| 18 |
|<img src="../photos/electronics/ServoPinB.png" alt="stretch_module" style="height:100px;">| 5 |
|<img src="../photos/electronics/ServoPinC.png" alt="stretch_module" style="height:100px;">| 15 |
|<img src="../photos/electronics/ServoPinD.png" alt="stretch_module" style="height:100px;">| 2 |
|<img src="../photos/electronics/ServoPinE.png" alt="stretch_module" style="height:100px;">| 0 |
|<img src="../photos/electronics/ServoPinF.png" alt="stretch_module" style="height:100px;">| 4 |
|<img src="../photos/electronics/ServoPinG.png" alt="stretch_module" style="height:100px;">| 17 |
|<img src="../photos/electronics/ServoPinH.png" alt="stretch_module" style="height:100px;">| 16 |

