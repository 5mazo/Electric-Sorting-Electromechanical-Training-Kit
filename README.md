# Electric-Sorting-Electromechanical-Training-Kit

# PLC-Based Metal and Non-Metal Sorting System

## 📌 Project Overview

This project involves the development of an automated material sorting training kit during my internship at **Jasa Kontrol Sdn Bhd**. The system identifies and sorts metal and non-metal blocks using sensors, a pneumatic gripper, and a pick-and-place mechanism controlled by a Siemens PLC.

The project also includes an HMI that provides manual and automatic operating modes, allowing users to monitor and control the sorting process.

## ⚙️ Hardware Components

- Siemens S7-1215 DC/DC/DC PLC
- Siemens SM1223 Digital I/O Module
- Metal Detection Sensor
- Encoder
- Limit Sensors
- Pneumatic Actuators and Gripper
- X and Z Motion Axes
- HMI Training Interface

## 💻 Software and Technologies

- **TIA Portal V16:** PLC programming and hardware configuration.
- **Ladder Logic:** System control and automation sequences.
- **HMI Development:** Operator interface for manual and automatic control.
- **Motion Control:** Positioning and movement control of X and Z axes.

## 🚀 Key Features and Implementations

### 1. Automated Material Sorting
- Detects and differentiates between metal and non-metal blocks.
- Implements a shift register to track and classify detected materials.
- Controls the pick-and-place sequence using a pneumatic gripper.

### 2. Motion Control
- Configured X and Z axes using Siemens Motion Control instructions.
- Implemented MC_MoveRelative for positioning and MC_MoveJog for manual movement.
- Used MC_Power and MC_Reset for axis control.
- Integrated encoder feedback and High-Speed Counters (HSC) for distance measurement.
- Configured limit sensors for motion safety.

### 3. HMI Development
- Developed an HMI for manual and automatic operation.
- Implemented real-time system monitoring and control.
- Updated PLC logic to support HMI functionalities.
- Organized program data using Function Blocks (FBs), Functions (FCs), and Data Blocks (DBs).

## 🎯 Skills and Knowledge Gained

- Siemens S7-1200 PLC Programming
- TIA Portal V16
- Ladder Logic Programming
- Industrial HMI Development
- Motion Control and Axis Configuration
- High-Speed Counter (HSC)
- Encoder-Based Distance Measurement
- Shift Register Implementation
- Function Blocks (FB), Functions (FC), and Data Blocks (DB)
- Industrial Automation and Troubleshooting

## 🏢 Internship

**Company:** Jasa Kontrol Sdn Bhd  
**Project:** Metal and Non-Metal Sorting Training Kit  
**Platform:** Siemens S7-1200 PLC  
**Software:** TIA Portal V16

---

*This project was developed as part of my industrial internship, providing hands-on experience in PLC-based automation, motion control, and HMI development.*
