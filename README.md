# 🕷️ Spider Mimic Quadruped

A biomimetic four-legged robot designed to replicate the movement of a spider. Built using Arduino, servo motors, and 3D-printed parts, this quadruped demonstrates simple gait algorithms to perform forward locomotion using IoT-compatible hardware.

---

## 🎥 Demo

https://github.com/user-attachments/assets/9c402222-6050-4799-888d-9c17101c978d

---

## 🚀 Features

- Four legs with two degrees of freedom (DOF) each
- Spider-inspired walking gait
- Controlled via Arduino
- Designed using 3D-printed components
- Potential for IoT or wireless control

---

## ⚙️ Technologies Used

- **Microcontroller**: Arduino Uno/Nano
- **Actuators**: Servo Motors (SG90 or MG90s)
- **Programming**: Embedded C/C++ (Arduino IDE)
- **Design Tools**: Fusion 360, TinkerCAD
- **Electronics**: Breadboard, circuit components

---

## 📂 Folder Structure

```

Spider-mimic-quadruped/
├── firmware/             # Arduino code for gait control
├── hardware/             # 3D models and schematics
├── images/               # Project images and diagrams
└── README.md

````

---

## 🔧 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yashgolani28/Spider-mimic-quadruped.git
   cd Spider-mimic-quadruped

2. **Assemble the Hardware**

   * 3D print the robot chassis and leg components.
   * Connect the servo motors to the Arduino as per the provided schematics.

3. **Upload the Firmware**

   * Open the Arduino IDE.
   * Load the `firmware/spider_quadruped.ino` sketch.
   * Select the appropriate board and port.
   * Upload the code to the Arduino.

---

## 🧪 How It Works

The robot uses a simple gait algorithm to mimic spider-like movement. Each leg has two degrees of freedom, allowing for coordinated motion that results in forward locomotion. The servos are controlled via PWM signals from the Arduino, executing predefined sequences to achieve the desired gait.

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/yashgolani28) or open an issue on this repository.

