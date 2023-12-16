---
title: "Microfluidic Device"
excerpt: "December 2023"
header:
  image: /assets/img/microfl_5.png
  teaser: /assets/img/microfl_5.png
gallery:
  - url: /assets/img/microfl_1.png
    image_path: assets/img/microfl_1.png
    alt: "microfluidic mold"
  - url: /assets/img/microfl_3.png
    image_path: assets/img/microfl_3.png
    alt: "microfluidic device"
  - url: assets/img/microfl_6.png
    image_path: assets/img/microfl_6.png
    alt: "microfluidic device in action"
---



## Description

The mold was designed using Fusion360 and was designed to create a silicon microfluidic device consisting of three distinct sections of channels. In the first section, two inlets are merged through alternating meander-shaped channels and inclined mixer channels, all measuring 750 micrometers in width. The second section introduces a third inlet, incorporating a zigzag mixing pattern within channels of the same 750 micrometer width. The third section, directly connected to the second, features snaking channels of 750 micrometers in width, with 500 micrometer wide perforations that allow for mixing before all of the liquid is gathered and sent through the outlet port. The overall mold, created with resin through SLA printing, encases a microfluidic device measuring 25 by 75 mm, with internal features strategically positioned at least 4 mm away from the edges.

The shape and dimensions of the channels were determined based on results of two research papers (cited below) and an initial test print. The research articles presented these four mixing channel methods to have the highest efficiency when mixing, and the scale of these features was a compromise between thin features that allow for little waste in the microfluidic and wider features that are stable enough to avoid damage during the post processing phase.

Vat photopolymerization, also known as SLA printing, was chosen as the manufacturing method for the mold due to its high resolution and small minimum feature size at 85 μm and 25 μm, respectively. Despite its advantages, the main drawback of this technique lies in the potential interference from parylene, which can compromise the high-resolution features during the curing process, leading to warping and the risk of uncured resin negatively impacting the final product. Post processing also proved to be challenging as it was difficult to clean off uncured resin without damaging the delicate extrusions.


## Printing & Processing
The mold for the microfluidic device was printed on a Form 3+ SLA printer. The print was generated from the .stl file using Preform software on the highest resolution setting and took approximately 4 hours to complete. After printing and removing from the bed, the mold was thoroughly cleaned in the wash and wiped down with isopropanol. The part was cured for 50 minutes before removing all support material.


## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e30b7e56fd334952a?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


## Multimedia
{% include gallery caption="microfluidic device as a mold, silicon, and working" %}

<youtube video here>
<iframe width="315" height="560"
src="https://youtu.be/gWlWB2crxE8"
title="Microfluidic Device"
frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
allowfullscreen></iframe>


## Citations
Microfluidic Mixing: A Review. Int J Mol Sci.12(5): 3263–3287.
Rapid prototyping of cell culture microdevices using parylene-coated 3D prints Lab Chip, 2021, 21, 4814-4822
