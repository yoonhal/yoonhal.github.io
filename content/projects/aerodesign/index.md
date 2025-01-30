---
title: UBC AeroDesign
description: My work on UBC Aerodesign.
date: 2021-09-06
weight: 1
---

# (This page is a WIP)

## TLDR;
Led the structural design of the fuselage of a 
super-lift RC aircraft that weighed ~3lbs 
empty and flew with 2.2 lbs of water. I used 
FEA to optimize for weight-to-strength and 
performed physical validation via bending 
and torsional tests. I communicated with the electrical teams to 
manage wire/component layout, the 
wing team to design a flow-transition region, 
and delegated tasks in my own team 
to design and build empennage connections and landing gears.

[Watch it fly!](#video)

### 2023-24 "Sonic"
<img class="thumbnailshadow" src="img/mcr_plane.png"/>
<img class="thumbnailshadow" src="img/sonic.png"/>

## About AeroDesign
UBC AeroDesign participates in SAE's Aero Design annual competition,
 competing with 40+ teams in Micro, Regular, and Advanced class categories,
 each category presenting a different engineering challenge.

### Micro Class
The main design objectives in micro class are:
- Minimize size (wingspan + length)
- Minimize empty weight (total weight - payload)
- Fast take-off
- Carry water payload

### Regular Class
The main objectives in regular class are:
- Heavier payload
- Larger wing span

## Micro Team Lead
As the lead for UBCAD's micro class team over the 2023-24 design cycle, I played a large role
in the design and construction of the main fuselage, water payload container, electrical layout,
and interfaces with parts such as landing gear, empennage, and wings.

### Structural Analysis
The fuselage's main structural members were built of two longitudinal plywood ribs spanning the payload container's width.
The design was iterated through and tested in FEA (SolidWorks) and physical testing to optimize the thickness and width of the members.
Stiffeners were used to increase the stiffness along the lateral axis and mitigate twisting. Shear and bending analysis were also conducted to determine the optimal 
number, placement, size, and material of key stiffeners.

<img class="thumbnailshadow" src="img/FEA.png"/>

In FEA, I chose a larger-than-typical safety factor (2.8, normally ~1.2-1.4 for aircraft to reduce weight) to account for plywood’s anisotropic nature, unaccounted in simulation. To further validate the analysis, bending and torsional testing was done on a prototype fuselage.

<img class="thumbnailshadow" src="img/physical_validation.png"/>

Testing showed that the fuselage could resist wing torsion up to a load factor of 3 and static load up to a load factor of 3.2 - leading to a FoS of 1.4.
In the image above, excessive buckling and local failure can be seen at a load factor of 3.2, with ultimate failure at a load factor of 4.2. The final design included more lateral stiffeners to resist buckling and gussets to increase local stiffness.

### Managing a Team
...


## Regular class

### 2022-23 "Indomitable"
<img class="thumbnailshadow" src="img/indomitable.jpg"/>
<img class="thumbnailshadow" src="img/indomitable_solo.jpg"/>

### 2021-22 "Snorlax"
<img class="thumbnailshadow" src="img/snorlax_team.jpg"/>

## Video
Watch it fly (and land):
{{< drive id="1uOOoVNV6pV89PoSJKm0G0iQgKjgImtV7" type="preview" >}}