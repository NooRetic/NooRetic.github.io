---
title: "Adaptive robotic system for the inspection of aerospace slat actuator mount"
collection: publications
permalink: /publication/2024-10-01-paper-title-number-2
excerpt: 'This paper presents a robotic inspection system used to inspect a slat actuator mount '
date: 2023-10-01
venue: 'Frontiers: Robotics and AI'

---
This paper introduces a robotic visual inspection system using off-the-shelf components able to inspect the mounting holes for wing slat actuators without the need for fixed-coordinate programming; the part just needs to be left within reach of the robot. Our system sets one of the opposed pairs of mounting holes as a reference (the “datum”) and then compares the tilt of all other pairs of mounting holes with respect to it. Under the assumption that any deviation in the mounting hole tilt is not systematic but due to normal manufacturing tolerances, our system will either guarantee the correct alignment of all mounting holes or highlight the existence of misaligned holes. Computer-vision tilt measurements are performed with an error of below 0.03° using custom optimization for the sub-pixel determination of the center and radius of the mounting holes. The error introduced by the robot’s motion from the datum to each of the remaining hole pairs is compensated by moving back to the datum and fixing the orientation again before moving to inspect the next hole pair. This error is estimated to be approximately 0.05°, taking the total tilt error estimation for any mounting hole pair to be 0.08° with respect to the datum. This is confirmed by manually measuring the tilt of the hole pairs using a clock gauge on a calibrated table (not used during normal operation).

citation: 'Morsi NM, Mata M, Harrison CS and Semple D (2024) Adaptive robotic system for the inspection of aerospace slat actuator mount. Front. Robot. AI 11:1423319. doi: 10.3389/frobt.2024.1423319'

[(Paper_link)](http://NooRetic.github.io/files/paper4.pdf)

 
