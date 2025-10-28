---
title: "SRFS: Parallel Processing Fault-tolerant ROS2-based Flight Software for the Space Ranger CubeSat"
collection: publications
category: manuscripts
permalink: /publication/2024-12-01-srfs-flight-software
excerpt: 'A satellite flight software system based on ROS2 that addresses the parallel performance limitations of traditional RTOS while ensuring efficient parallel data processing and system reliability.'
date: 2024-12-01
venue: 'arXiv (under review)'
slidesurl: # URL to slides if available
paperurl: 'https://arxiv.org/abs/2412.08164'
citation: 'Zhao, Z., Xiang, Y., Zhou, Z., Chong, K., Ma, H., & Chen, P. (2024). &quot;SRFS: Parallel Processing Fault-tolerant ROS2-based Flight Software for the Space Ranger CubeSat.&quot; <i>arXiv preprint arXiv:2412.08164</i>.'
---

## Abstract

Traditional real-time operating systems (RTOS) often exhibit poor parallel performance, while thread monitoring in Linux-based systems presents significant challenges. To address these issues, this paper proposes a satellite flight software system design based on the Robot Operating System (ROS), leveraging ROS's built-in reliable publish-subscribe messaging mechanism for inter-application communication.

Considering the complex functional requirements of modern small satellites, the design incorporates both hardware and software architecture, alongside system scheduling and error-correction mechanisms. This approach ensures efficient parallel data processing and system reliability, while also reducing the development cycle through code reuse.

Comprehensive testing, including system time delay, system management, fault tolerance, and system maintenance, was conducted to validate the system's capabilities in telemetry, remote control, new feature integration, and autonomous error correction. The results demonstrate the high reliability and ease of maintenance of the satellite flight software offering a reference framework for the rapid development of high-performance small satellite operations systems.

This work is currently under further review and available on arXiv.
