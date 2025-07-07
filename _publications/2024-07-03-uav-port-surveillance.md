---
title: "Optimizing Computational Load and Energy Efficiency in UAV-Based Port Surveillance System"
collection: publications
category: conferences
permalink: /publication/2024-07-03-uav-port-surveillance
excerpt: 'A UAV-based system for detecting unauthorized vessels in ports using image stitching, sensor fusion, and real-time object detection with YOLO on edge hardware.'
date: 2024-07-03
venue: '2024 IEEE International Conference on Signal Processing, Communications and Computing (ICSPCC)'
paperurl: '/files/uav-port-surveillance.pdf'
citation: 'H. Sureshkumar<sup>*</sup>, S. Gharat, D. Ambre, L. Shetty, A. Kadam, D. Ansari, and G. Birajdar, "Optimizing Computational Load and Energy Efficiency in UAV-Based Port Surveillance System," in <i>Proc. IEEE ICSPCC</i>, 2024.'
---

This paper presents a UAV-based surveillance system that enhances maritime safety by detecting unauthorized vessel entries in restricted port areas. The system employs a combination of sensor fusion, image stitching, and deep learning-based object detection (YOLO with MobileNet 0.75) on edge devices like the Sipeed Maixduino K210.

A Pub-Sub communication model using Apache Kafka enables real-time image sharing and vessel coordinate transfer between drones and a centralized Maritime Information System (MIS). The architecture is optimized using a DroneBalance algorithm for efficient energy use and task distribution among drones.

The system achieves a validation accuracy of 78.5% after 90 epochs of training on a custom dataset, demonstrating the potential for real-time, onboard maritime surveillance at scale.
