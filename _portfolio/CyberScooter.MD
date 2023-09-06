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

Up until recently I rode a Gotrax E-Scooter to work every day. The scooter retailed for $300, but it quickly paid for itself after I was able to forgo gas and a parking spot at work. However, after about a year and a half of driving the scooter daily the battery started to lose charge quickly and there were a couple other mechanical issues that forced me to stop riding the scooter. Instead of purchasing a new scooter, I decided to go the DIY route to build a one-off scooter that fits my needs.

{% include gallery caption="This is a sample gallery to go along with this case study." %}



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
| Content Cell  | 1  |
| Content Cell  | 1  |

### 


{% include gallery caption="This is a sample gallery to go along with this case study." %}
