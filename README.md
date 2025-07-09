# Smart Library Monitoring System

This repository showcases the **Smart Library Monitoring System**, a computer vision-based project developed in collaboration with **TED University**. The project is officially approved by the university and is being implemented in our **campus library**.

## 🎯 Project Overview

- A ceiling-mounted camera system captures still images every 20 seconds.
- Each frame is analyzed using **YOLOv8 (Ultralytics)** for real-time object detection.
- Individual desk areas are defined using polygonal regions.
- Occupancy is determined by combining object detection with **SSIM (Structural Similarity Index)** image comparison.
- Each area (spot) is classified as:
  - ✅ **EMPTY**
  - 🧍‍♂️ **OCCUPIED**
  - ⏳ **HOLD** (transitional state)

## 🔧 Current Status

We are currently in the **hardware setup and system testing phase**. Cameras are being installed and initial evaluations are being conducted within the TED University Library with full institutional support.

## 📁 Repository Contents

This public repository is intended for **demonstration and presentation purposes**. It includes:

- 🎥 A **demo video** of the system in action.
- 📊 **Presentation slides** explaining the system architecture and goals.
- 📝 A summary of the **project objectives**, methods, and applications.

> **Note:**  
> The source code is hosted in a private repository during development.

---

Made with ❤️ at **TED University**.
