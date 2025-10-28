---
title: "Enhancing CubeSat Reliability and Efficiency: An Approach to Hot Redundancy with Heterogeneous Hardware-software Architecture"
collection: publications
category: conferences
permalink: /publication/2024-10-01-cubesat-reliability
excerpt: 'A CubeSat system solution featuring heterogeneous hardware and software with multi-processor hot redundancy, characterized by high real-time performance, reliability, and energy efficiency.'
date: 2024-10-01
venue: 'International Astronautical Congress (IAC) 2024'
slidesurl: # URL to slides if available
paperurl: 'https://www.scopus.com/record/display.uri?eid=2-s2.0-85219206175&origin=resultslist'
citation: 'Xiang, Y., Zhao, Z., Zhou, Z., & Chen, P. (2024). &quot;Enhancing CubeSat Reliability and Efficiency: An Approach to Hot Redundancy with Heterogeneous Hardware-software Architecture.&quot; <i>Proceedings of the International Astronautical Congress (IAC)</i>. Milan, Italy. DOI: 10.52202/078365-0076'
---

## Abstract

CubeSat integrated electronic systems based on Commercial Off-The-Shelf (COTS) components face reliability challenges. Current research on enhancing system reliability primarily focuses on multi-hardware homogeneous hot redundancy and multi-system cold redundancy. However, the hot redundancy of multiple homogeneous high-performance processors is challenging for CubeSats due to their limited energy sources and high-power requirements. Multi-system cold redundancy experiences long activation times during problems, failing to maintain stable program operation, which adversely affects the real-time performance of the system.

This paper proposes a **CubeSat tight system solution** that incorporates heterogeneous hardware and heterogeneous software with multi-processor hot redundancy, characterized by high real-time performance, high reliability, and high energy efficiency.

### Key Features

**Multi-Processor Hot Redundancy**: Through a scheduling system and its peripheral hardware, this solution achieves mutual hot redundancy among multiple hardware components, allowing the continuous operation of the main program while simultaneously performing hardware reboot and error correction on any processor encountering errors.

**Heterogeneous Processing Architecture**:
- High-performance processors handle real-time image processing tasks and simultaneously carry out satellite telemetry and telecontrol (TT&C) tasks
- Low-power processors are dedicated solely to satellite TT&C tasks

**FPGA-Based Coordination**: An FPGA achieves the time synchronization of heterogeneous processors and implements a two-out-of-three arbitration mechanism for TT&C instruction processing, ensuring instruction accuracy while monitoring processor operational status.

**Dual Operating System Design**:
- High-performance processors employ ROS2 on Linux to harness multi-core parallel processing capabilities
- Low-power processors utilize FreeRTOS to meet real-time requirements

### Application

This solution is set to be applied to a 3U CubeSat scheduled for launch in late 2024.

**Presentation**: Oral presentation at IAC 2024, Milan, Italy
**DOI**: 10.52202/078365-0076
