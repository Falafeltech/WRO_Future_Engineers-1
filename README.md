Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2022.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Introduction

Hello everyone,

We are the [Barq Engineers] from Palestine. We are a group of three ambitious young men: Amjad Ghannam, Rayan Farid, and Qusay Laila , with our car {BURAQ} represents not only our drive for technological advancement but also a symbol of hope and aspiration for the people of Palestine. Burag reflects the speed and brilliance of this legendary creature, embodying our ambition to overcome obstacles and make a mark on the world stage. Through Burag, we aim to demonstrate the remarkable achievements that Palestinian youth can accomplish, even in the face of adversity. .

In this competition, our goal is to showcase to the world what Palestinian youth can achieve, even under the harsh conditions of occupation. Through our efforts, we aim to send a powerful message about resilience, creativity, and the limitless potential that exists within every Palestinian boy.

## contact with us:
* Amjad Ghannam _email:amjadgh72@gmail.com
                _whatsapp:+972594387565

* Rayan Farid _email :rayanplaystation180@gmail.com
              _whatsapp: +972568997345

* Qusay Laila _email :qusaylaila.work@gmail.com
             _whatsapp: +972592509054

## The coach:
Eng.Mohammad Muamar...

a palestinian engineer and graduate of Palestine Polytchnic University in Hebron http://mailto:info@ppu.edu/ We extend our heartfelt gratitude to our coach for all he has done for us, especially during the challenging times. His unwavering support and dedication have been invaluable. If you wish to reach out to him, feel free to contact him via email moh.mummar@gmail.com or phone +970594958003

## Barq team's social accounts

## Overview
Our car is built on an RC structure featuring four wheels and a rear-wheel drive system. It is powered by a DC motor that controls the wheels and a servo motor for steering. The car is equipped with three ultrasonic sensors , gyroscope and a RGB color sensor to ensure it stays on the right path.

On the second level of the structure, we have placed the Arduino controller and the Raspberry Pi, along with a 12-volt battery down in the first floor, a camera, and other components that will be detailed in the parts section.


## components:
| Quantity | Status                             | Description                                                                                                                                             |
| ---------| ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1        | Raspberry Pi 4 Model B             |https://www.raspberrypi.com/products/raspberry-pi-4-model-b/                   |
| 1        | *Arduino Mega:          | (https://store.arduino.cc/products/arduino-mega-2560-rev3)            |
| 1        | The L298N Motor Driver:                     | https://components101.com/modules/l293n-motor-driver-module                         |
| 1       | Servo motor MG996r          |https://www.jsumo.com/mg996r-servo-motor-digital |
| 1 | pixy2 camera| https://pixycam.com/pixy2/   |
| 1      | MPU-9250       |https://learn.sparkfun.com/tutorials/mpu-9250-hookup-guide/all         |
| 3        | *HC-SR04 Ultrasonic Sensor  | https://www.sparkfun.com/products/15569 |
|1      | TCS3200 Sensor        | https://www.adafruit.com/product/1334   |
|1      | lithum Battery 12v     | https://www.amazon.in/INVENTO-1Pcs-11-1V-55x65x18mm-Rechargeable/dp/B072SPSG2W   |
|1      | HW-083       | https://www.elektormagazine.com/labs/hw-083-hack-evolution-charger   |

## How to prepare the repo based on the template

_Remove this section before the first commit to the repository_

1. Clone this repo by using the `git clone` functionality.
2. Remove `.git` directory
3. [Initialize a new public repository on GitHub](https://github.com/new) by following instructions from "create a new repository on the command line" section (appeared after pressing "Create repository" button).
