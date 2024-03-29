---
title: "Getting Started"
date: 2023-01-01 00:00:00 +0000
categories: [Documentation, Getting Started]
tags: [verso, tutorial]
pin: true
math: true
mermaid: true
author: <verso>
---


# Introduction

The Verso Platform is an accessible hub for robotic enthusiasts and students to craft robotic arms. It is designed to be easy to assemble and program and is a great way to learn about robotics. The entire robotic arm project is intentionally budget-friendly, with a total cost estimated at under $400. We created 2 versions of the robotic arm, which each use the Verso platform to build custom robotic arms. We offer two distinct examples of 6-axis robotic arms, known as the Verso Arm S and Verso Arm N, using the versatile Verso platform.

[**Image Gallery**](https://versorobotics.com/posts/gallery/)

## Electronics

![PCB](/assets/img/electronics/thumbnail.png){: .shadow .rounded-100}

At the heart of the Verso Platform lies a custom-designed Printed Circuit Board (PCB) configured to connect motors, sensors, and additional features to the microcontroller (MCU). The primary MCU in use is the Teensy 4.1, with compatibility with up to six stepper motors and nine limit switches, forming the nervous system of your robotic arm.

[**Electronics**](https://versorobotics.com/posts/electronics/)

## Cycloidal Actuators

![Our Cycloidal Actuator](/assets/img/gearboxes/thumbnail.png)

The Verso Platform features two meticulously designed cycloidal gearboxes with different ratios, offering flexibility and adaptability to your project. These gearboxes come in 1:24 and 1:11 ratios, designed to be easily assembled and produced using 3D printing, laser cutting, or CNC milling techniques. They were created with our epitrochoid function generator, which is below - though feel free to use our existing files, they are very versatile!

[**Cycloidal Actuators**](https://versorobotics.com/posts/gearboxes/)

## Cycloid Function Generator

![Desmos Animation](/assets/img/cycloid_gen/cycloidgif.gif)

The Cycloidal Function Generator is an open-source tool crafted to facilitate the creation of cycloidal gears through parametric design. Utilizing the Desmos API, this tool allows the generation of epitrochoid functions, which represent the path traced by a point on a circle as it rolls around the exterior of another circle. This functionality is crucial for designing complex mechanical systems like the Verso arm's actuators.

[**Cycloid Generator**](https://versorobotics.com/posts/generator/)

## Bill of Materials

The Verso Platform is designed to be easy to source and manufacture. The bill of materials includes links to purchase the components and the CAD files for the components.
![BOM](/assets/img/VersoBOM.png){: .shadow .rounded-100}
[**Bill of Materials**](https://versorobotics.com/posts/bom/)

## Assembly

Both the Verso Arm S and Verso Arm N are tailored for production with hobbyist-grade 3D printers and laser cutters. While they share the Verso Platform as their foundation, each embodies unique design aesthetics to showcase the versatility of the platform.

![Assembly](/assets/img/gallery/1.png)

[**Assembly**](https://versorobotics.com/posts/assembly/)
