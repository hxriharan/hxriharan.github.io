---
title: "Cygnus: A Vision-Based Drone System for Drowning Detection Using IoT"
collection: publications
category: conferences
permalink: /publication/2024-07-03-cygnus-drowning-detection
excerpt: 'Cygnus is a vision-based drone system designed for real-time drowning detection using IR/RGB fusion, YOLOv8, edge computing, and LoRa-based communication.'
date: 2024-07-03
venue: '2024 2nd International Conference on Recent Trends in Microelectronics, Automation, Computing and Communications Systems (ICMACC)'
paperurl: '/files/cygnus-drowning-detection.pdf'
citation: 'H. Sureshkumar*, D. Ambre, P. Trivedi.'
---

This paper presents Cygnus, an innovative UAV-based system designed to detect drowning incidents in real time using vision-based techniques. By fusing RGB and infrared imagery and deploying a YOLOv8 model on GAP8 edge microcontrollers onboard drones, Cygnus enables robust monitoring even in low-light or complex aquatic environments.

The system integrates a LoRa-based wireless sensor network (WSN) for drone-to-drone and drone-to-server communication, an on-board image processing pipeline, and a lifeguard-facing web dashboard. A DroneZoom technique is employed to optimize image resolution in ambiguous situations by adjusting drone altitude dynamically.

Cygnus achieves a precision of 95% and a mean Average Precision (mAP) of 83% on a custom dataset of 1000 annotated aquatic activity images. Its modular architecture includes sensor fusion, onboard edge processing, autonomous drone routing, and LoRa WAN coordination — making it a powerful tool for enhancing water safety and enabling rapid response during emergencies.
