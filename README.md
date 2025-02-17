# Monocular Distance Estimation and YOLOv8 for Robotic Arm Pick-and-Place Tasks

## Overview

This repository focuses on the application of monocular distance estimation combined with YOLOv8 (You Only Look Once, version 8) to guide robotic arms for pick-and-place tasks. The goal is to leverage low-cost computer vision techniques for spatial localization and real-time object detection, enabling efficient and precise robotic operations.

## Key Features

- **Monocular Distance Estimation:** Uses a single camera for depth estimation, offering a cost-effective solution for spatial localization in low-cost robotic systems.
- **YOLOv8 Object Detection:** Real-time detection of objects with high accuracy, even in cluttered environments, essential for identifying and localizing objects in pick-and-place tasks.
- **Robotic Arm Integration:** Provides methods for integrating the vision system with robotic arms, ensuring that detected objects are appropriately picked and placed.
- **Optimized Vision Pipeline:** Focuses on efficient processing and reduced computational overhead, addressing hardware limitations common in low-cost robotic systems.

## Challenges Addressed

Integrating monocular depth estimation and YOLOv8 into low-cost robotic systems presents challenges related to:
- **Computational Constraints:** Ensuring that the system runs efficiently on hardware with limited resources.
- **Hardware Limitations:** Designing a vision pipeline that is both cost-effective and capable of real-time performance.
- **Smooth Joint Motion:** Tailoring inverse kinematics models to the robotic arm’s design to ensure fluid and precise joint movements during pick-and-place operations.
