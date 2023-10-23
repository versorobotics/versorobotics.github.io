---
title: "Robotic Arm Project"
date: 2023-10-23 12:00:00 +0000
categories: [Robotics, Tutorial]
tags: [robotic-arm, tutorial, jekyll]
author: AUTHORNAME
image:
  path: /assets/img/robotic-arm.jpg
  alt: "Robotic Arm"
---

# Introduction
Welcome to my blog post about building a robotic arm!

## Materials Needed
- Servo motors
- Arduino board
- Jumper wires
- Breadboard
- Power supply

## Building the Robotic Arm
1. Assemble the base of the robotic arm.
2. Connect the servo motors.
3. Wire up the Arduino board.

## Programming
Here's a simple Arduino code snippet for your robotic arm:


```c++
#include <Servo.h>
Servo myservo;
void setup() {
  myservo.attach(9);
}
void loop() {
  myservo.write(90);
  delay(1000);
  myservo.write(0);
  delay(1000);
}
```
{: file="arduino_sketch.ino" }

