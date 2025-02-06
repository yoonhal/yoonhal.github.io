---
title: Autonomous Racing Robot
description: A project course designing robots.
date: 2023-08-25
weight: 2
---

## TLDR;

Built a robot capable of autonomously navigating a 
competition "race track" in a small team of 4. Took charge 
designing the chassis, steering mechanism, motor driver, 
and competition strategy, playing a pivotal role in allowing 
our team to become one of only two teams to successfully 
take a shortcut, a handful to complete a lap, all while being 
one of the fastest robots (finishing laps in ~10 seconds).

## About the competition
(WIP)...

## Mechanical Contributions
- Iterated numerous virtual and physical prototypes for chassis, steering mechanism, circuit board mounts, suspension system, and bumper design
- Spearheaded the design and oversaw the manufacturing of the final aluminum chassis
- Developed the ackerman-like steering geometry

## Electrical Contributions
- Soldered and tested four custom full H-Bridges for motor control
- Validated circuit designs in Altium and troubleshot EMI noise issues from motor and more

## Software Contributions
- Developed a high-level state machine to implement competition strategy
- Utilized unstable breakdown point of sensors as map check-point triggers to mitigate IMU drift issues
- Tuned PID line following and steering control to tighten turn radius and speed

## Results
- Capable of withstanding rear, frontal, and side crashes from other robots and terrain
- Leap from a ramp ~1 ft high into pebbles with ease; 1 of 2 teams to successfully utilize this shortcut in this manner
- Quickly finished laps in [~10 seconds](#video)
- All accomplished within a few weeks

## Video
{{< drive id="1hD8sNTtov9rAoVI1K7JCEI6z_IZ1vWbB" type="preview" >}}