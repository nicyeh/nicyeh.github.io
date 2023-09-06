---
title: "Syringe Pump"
excerpt: "in collaboration with Dzifa Dumenyo, Ethan Smiley, and Fae Katras."
header:
  image: /assets/img/Cyber-Scooter-Banner.jpg
  teaser: /assets/img/Cyber-Scooter-TH.jpg
gallery:
  - url: /assets/img/Cyber-Scooter-1.jpg
    image_path: assets/img/Cyber-Scooter-1.jpg
    alt: "placeholder image 1"
  - url: /assets/img/Cyber-Scooter-2.jpg
    image_path: assets/img/Cyber-Scooter-2.jpg
    alt: "placeholder image 2"
  - url: /assets/img/Cyber-Scooter-3.jpg
    image_path: assets/img/Cyber-Scooter-3.jpg
    alt: "placeholder image 3"
---

{% include gallery caption="Large Format 3D Printer Gallery" %}

### WHAT:  
a fully automated, user-friendly syringe pump that can be manufactured at a low cost.
### WHY:  
this simple but effective device is essential to the healthcare industry. If needed, this design can be replicated quickly for emergency/low cost use.
### HOW:  
basic components (stepper motor, lead screw, potentiometer, Arduino) used in a cohesive design in combination with 3D printed pieces.

## Skills developed:  
CAD & dimensioned drawings (Fusion 360), programming (C++), wiring & soldering, iterative design

## Features include:  
* Nema 17 stepper motor coupled to an 8mm lead screw
* custon 3D printed PLA syringe holders driven by the stepper motor on the lead screw
* 200 mm linear rod to stabilize syringe pump
* Latching button to start, pause, and resume actuation
* Potentiometer that adjusts flow rate (0.08 to 4 mL per min)
* LED to indicate syringe state (full, paused, empty)
* LCD showing flow rate and time until empty
* Limit switch used to stop actuation when syringe is empty
* Arduino Uno and A4988 stepper driver controlling stepper motor from inputs
* powered by Mean Well RQ-65D AC-DC power supply
* custom 3D printed PLA base with a sliding lid, enclosing all electrical components

## CAD Model:
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e438cdf6d181a387965?mode=embed" 
width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Parts Guide:
### Off-the-shelf Parts:
| Part  | Quantity |
| ------------- | ------------- |
| Nema 17 stepper motor  | 1  |
| 8mm lead screw  | 1  |
| 200 mm linear rod  | 1  |
| Latching button  | 1  |
| Potentiometer  | 1  |
| LED  | 1  |
| LCD  | 1  |
| Limit Switch  | 1  |
| Arduino Uno  | 1  |
| A4988 stepper driver  | 1  |
| Mean Well RQ-65D AC-DC power supply  | 1  |

### 3D printed parts:
| Part  | Quantity |
| ------------- | ------------- |
| Enclosure body  | 1  |
| Enclosure lid  | 1  |
| Syringe holder  | 3  |
| Motor mount (ABS) | 1  |


### How to operate:  
1. Plug in syringe pump  
2. Fill syringe with desired amount of liquid and place in syring holders  
3. Adjust potentiometer to desired flow rate as indicated on LCD  
4. Press button to start, pause, or stop the flow

Find Arduino Uno code [here.](github.com/nicyeh/assets/syringepump-code)

### Drawings:
<img src="/assets/img/drawing_1" alt="drawing 1" style="width:200px;"/>
<img src="/assets/img/drawing_2" alt="drawing 2" style="width:200px;"/>
<img src="/assets/img/drawing_3" alt="drawing 3" style="width:200px;"/>
