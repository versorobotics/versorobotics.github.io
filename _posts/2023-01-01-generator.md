---
title: "Cycloid Function Generator"
date: 2023-01-01 00:00:00 +0000
categories: [Documentation, Hardware]
tags: [verso, tutorial]
author: <verso>
pin: true
math: true
image: 
    path: /assets/img/gallery/cycloidgif.gif
---

The Cycloidal Function Generator is an open-source tool crafted to facilitate the creation of cycloidal gears through parametric design. Utilizing the Desmos API, this tool allows the generation of epitrochoid functions, which represent the path traced by a point on a circle as it rolls around the exterior of another circle. This functionality is crucial for designing complex mechanical systems like the Verso arm's actuators.

<iframe style="width: 100%; height: 30rem; border-radius: 18px;" scrolling="no" title="desmos" src="https://codepen.io/nikhil-k-v/embed/YzOyYpx?default-tab=" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/nikhil-k-v/pen/YzOyYpx">
  desmos</a> by nv (<a href="https://codepen.io/nikhil-k-v">@nikhil-k-v</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

## Features

### Parameters
Adjust the following parameters to define your gear's design:
- `R` - Overall radius
- `N` - Number of teeth/pins
- `S` - Radius of pins
- `E` - Eccentricity

### Fusion 360 Integration: 
The tool is compatible with the Equation Driven Curve Add-In in Fusion 360, offering a seamless workflow for CAD modeling.
### Customization:
A slider is available to adjust the number of teeth/pins, and additional functions are included for experimental purposes. Users can also animate the cycloid to visualize the gear's motion.

## Usage
To utilize the generator:
- Input your parameters into the provided format.
- Use the embedded generator below or access the exportable cycloid via the provided link.
- Add your function into Fusion 360 using the Equation Driven Curve Add-In.

[Link to Desmos Generator](https://www.desmos.com/calculator/qfcupuubfp)


## Epitrochoid Function Equations

The parametric equations for our epitrochoidal gears are as follows:

$$ x(t) = R \cdot \cos(t) - S \cdot \cos\left(t + \arctan\left(\frac{\sin((1 - N) \cdot t)}{\left(\frac{R}{E \cdot N}\right) - \cos((1 - N) \cdot t)}\right)\right) - E \cdot \cos(N \cdot t) $$

$$ y(t) = R \cdot \sin(t) - S \cdot \sin\left(t + \arctan\left(\frac{\sin((1 - N) \cdot t)}{\left(\frac{R}{E \cdot N}\right) - \cos((1 - N) \cdot t)}\right)\right) - E \cdot \sin(N \cdot t) $$
