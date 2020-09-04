---
layout: project
type: project
image: images/rover.jpg
title: Rover
permalink: projects/Rover
# All dates must be YYYY-MM-DD format!
date: 2018-10-23
labels:
  - Robotics
  - Raspberry Pi
  - Python
summary: I was tasked to create a rover that was able to be controlled through the use of a computer and that could also be autonomous.
---

  The final version of the rover that I ended up creating used a combination of three Ultra Sonic distance sensors and a much smaller infra-red sensor that were programmed to detect the distances of objects all around the actual rover. If a cetain object was too far or too close, the rover would adjust accordingly to aviod crashing into the object and to stay in a sort of "center" area between the objects surrounding it.
  When it came to the use of controlling the rover throught a computer, the computer connected to the rover's raspberry Pi via Putty using an SSH connection. Any and all programs that were used by the rover through the Raspberry Pi were written in Python.
