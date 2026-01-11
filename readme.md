# MyCobot ROS 2 Simulation (Jazzy + Gazebo)

This repository contains a ROS 2 Jazzy project for simulating and controlling a **MyCobot robotic arm** in **Gazebo**.  
The project demonstrates robotic arm motion.

The setup and simulation workflow is based on the tutorial by *Automatic Addison*.
https://automaticaddison.com/how-to-simulate-a-robotic-arm-in-gazebo-ros-2-jazzy/
---

## 📽️ Demo Video

A short demo video showing:
- Robotic arm movement in Gazebo
- Gripper opening and closing in a loop

👉 Google Drive link:  
https://drive.google.com/file/d/1UGC-lsCuxUVvOwnXVExyvPw5l2BE3mGL/view?usp=sharing

---

## 🚀 Features

- ROS 2 Jazzy based simulation
- Gazebo (gz-sim) integration
- MyCobot robot description (URDF/Xacro)
- Arm motion demo loop
- Gripper open/close control
- Launch files for easy startup

---

## 🧰 Prerequisites

Make sure the following are installed:

- Ubuntu (recommended: 22.04 or newer)
- ROS 2 Jazzy
- Gazebo / gz-sim compatible with ROS 2 Jazzy
- `colcon` build tools
- Git

Verify ROS 2 installation:
```bash
ros2 --version
