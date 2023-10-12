---
title: "Print-in-Place Pliers"
excerpt: "good"
header:
  image: /assets/img/plier cover.jpeg
  teaser: /assets/img/plier cover.jpeg
gallery:
  - url: /assets/img/plier insert.jpeg
    image_path: assets/img/plier insert.jpeg
    alt: "plier insert"
  - url: /assets/img/plier open.jpeg
    image_path: assets/img/plier open.jpeg
    alt: "placeholder image 2"
  - url: /assets/img/plier close.jpg
    image_path: assets/img/plier close.jpg
    alt: "placeholder image 3"
---

Print-in-place is a method of 3D printing that creates a complete, moveable part right off of the print bed. Multiple components are printed in their assembled configuration, allowing for complicated products to be created quickly and with little waste. Other print-in-place objects include hinges, articulating toys, and latching mechanisms.

<img src="/assets/img/pl.gif" alt="pliers gif" style="width:800px;"/>

This pair of print-in-place pliers was created as four separate components made of PLA and TPU. Due to a lack of availabiltiy of the dual-extruder printer, This design was produced in two separate print batches according to the filament material, and the final product was subsequently assembled. However, this print can easily be modified and printed all at once on a dual extruder.

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e30b7e56fd334952a?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## About the design

<img src="/assets/img/plier pieces.jpeg" alt="pliers gif" style="width:800px;"/>

The final product has three components: two interlocking PLA plier arms, a TPU spring, and a TPU band keeping the PLA joint together.

{% include gallery caption="Plier spring in both open and closed position." %}

This spring compression fits into slots on either plier arm and compresses when the mechanism is squeezed together. Due to its geometry, the spring pushes the pliers back to open position. It is printed on its side and is interchangeable to create pliers of different stiffnesses with the same configuration. The design is parameterized so that a stiffness coefficient can be changed to determine the thickness of the TPU spring (default coefficient of 1).

<img src="/assets/img/plier iterations.jpeg" alt="pliers gif" style="width:800px;"/>

Three iterations were required to get to this final product. The first (left) was created with minimal prior knowledge about plier geometry and served to help me more accurately scale the pliers to comfortable propotions. There were no connections or spring components. The second iteration (middle) solidified the base geometry and tested added a spring component and joint for the two arms. This design was a useful size and angle for holding, however the joint was not secure enough and the spring did not fit in its slots. The third and final iteration (right) kept the same basic geometry but utilized a larger TPU spring insert. A TPU band was also added around a larger swivel joint to further reinforce it for when pressure is applied to the handles. These modifications helped to produce a fully functional final pair of pliers.

## Specifications

* 12 mm jaw capacity
* 20 mm jaw length
* 85 mm handle length
* 24 mm uncompressed spring length
* 13 mm compressed spring length


## Print settings
Print 1 (PLA arms):
* Bed temperature: 65 degrees C
* Nozzle temperature: 205 degrees C
* Print speed: 100%

Print 2 (TPU spring and band):
* Bed temperature: 50 degrees C
* Nozzle temperature: 225 degrees C
* Print speed: 95%
