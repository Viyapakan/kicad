\# Project 02 – ESP32-S3 IoT Test Board (4-Layer PCB)



\## Overview



This project focuses on designing a custom ESP32-S3-based IoT development and testing board using \*\*KiCad 9\*\*.



The board is designed to provide a compact and versatile hardware platform for IoT prototyping, environmental monitoring, sensor interfacing, and embedded systems development.



The design follows a practical PCB development workflow, covering component selection, schematic design, footprint assignment, PCB layout, routing, and final design verification.



This project is developed as a hands-on learning exercise, following the YouTube tutorial referenced below.



\## Design Objectives



\- Design a custom PCB around an ESP32-S3 Wi-Fi module.

\- Develop a four-layer PCB layout for improved routing flexibility.

\- Integrate an environmental sensor for temperature and humidity monitoring.

\- Implement USB-C connectivity for power and programming.

\- Provide expansion interfaces for external sensors and peripherals.

\- Understand practical PCB design considerations, including component placement, routing, grounding, and power distribution.



\## Planned Hardware Features



| Component / Feature | Description |

|---|---|

| ESP32-S3 | Main Wi-Fi-enabled microcontroller module with 8 MB Flash |

| Si7021 | Temperature and relative humidity sensor |

| Qwiic Connector | Interface for connecting compatible external sensors |

| USB-C | Power supply and programming interface |

| BOOT Button | ESP32-S3 boot mode selection |

| RESET Button | Hardware reset |

| User Button | General-purpose user input |

| RGB LED | Programmable status indication |

| SPI Expansion | 2×5-pin SPI expansion header |

| Programming Header | 2×3-pin programming interface |

| Power LED | Indicates the presence of the 3.3 V power rail |



\## PCB Specifications



\- \*\*EDA Software:\*\* KiCad 9

\- \*\*Board Type:\*\* Four-layer PCB

\- \*\*Target Dimensions:\*\* 50 mm × 50 mm

\- \*\*Mounting:\*\* 4 × 3.2 mm mounting holes

\- \*\*Main Controller:\*\* ESP32-S3 Wi-Fi module

\- \*\*Power Interface:\*\* USB Type-C



\## Development Workflow



1\. Component research and selection

2\. Schematic capture

3\. Electrical Rules Check (ERC)

4\. Component footprint assignment

5\. PCB placement and board outline

6\. Four-layer PCB stack-up configuration

7\. Signal and power routing

8\. Design Rules Check (DRC)

9\. 3D PCB inspection

10\. Final design documentation and manufacturing preparation



\## Learning Outcomes



Through this project, I aim to strengthen my practical understanding of:



\- Professional schematic design using KiCad.

\- Four-layer PCB stack-up and routing strategies.

\- ESP32-S3 hardware integration.

\- Sensor interfacing and I²C communication.

\- USB-C power and programming circuit design.

\- PCB grounding, power distribution, and signal integrity.

\- Design Rule Checking and PCB manufacturing requirements.



\## Tutorial Reference \& Credits



This project is based on the following educational tutorial:



\*\*KiCad 9: Design an ESP32-S3 IoT 4-layer PCB with sensor and QWIIC interface. Complete Guide.\*\*



Original tutorial by the YouTube video creator:



\[Watch the original tutorial on YouTube](https://www.youtube.com/watch?v=QoU0WWNgO2g)



Full credit goes to the original creator for the tutorial, design guidance, and educational content. This repository documents my learning process and implementation while following the tutorial.



\---



\*\*Project Status:\*\* In Progress



\*\*Software:\*\* KiCad 10.0



\*\*Category:\*\* Embedded Systems | IoT Hardware | PCB Design

