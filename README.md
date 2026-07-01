# 🤖 Self-Balancing Robot

A two-wheeled **Self-Balancing Robot** built using **Arduino Uno**, **MPU6050 IMU sensor**, and a **PID (Proportional–Integral–Derivative) control algorithm**. The robot continuously measures its tilt angle and adjusts motor speed in real time to maintain an upright position, demonstrating the principles of control systems, embedded programming, and sensor fusion.

---

## 📌 Features

* ⚖️ Real-time self-balancing using PID control
* 📊 Tilt angle estimation using the MPU6050 accelerometer and gyroscope
* 🔄 Continuous feedback loop for stable balancing
* 🚗 Independent speed and direction control of both motors
* ⚡ Fast response to external disturbances
* 🔋 Battery-powered portable design

---

## 🛠️ Tech Stack

* **Microcontroller:** Arduino Uno
* **Programming Language:** Arduino C/C++
* **Sensor:** MPU6050 (Accelerometer + Gyroscope)
* **Motor Driver:** L298N
* **Motors:** DC Geared Motors
* **Power Supply:** 7.4V Li-ion Battery
* **Control Algorithm:** PID Controller

---


## ⚙️ Working Principle

1. The **MPU6050** continuously measures the robot's orientation.
2. Sensor data is processed to calculate the current tilt angle.
3. The **PID controller** compares the measured angle with the desired upright position.
4. Based on the calculated error, the controller adjusts the speed and direction of both motors.
5. This feedback loop repeats continuously, allowing the robot to balance itself in real time.

---

## 🔧 Hardware Components

* Arduino Uno
* MPU6050 IMU Sensor
* L298N Motor Driver
* 2 × DC Geared Motors
* 2 × Wheels
* Robot Chassis
* 7.4V Li-ion Battery
* Connecting Wires
* Power Switch

---


### Upload the Code

1. Open the project in **Arduino IDE**.
2. Install the required libraries:

   * MPU6050
   * I2Cdev
   * Wire
3. Connect the Arduino Uno.
4. Select the correct board and COM port.
5. Upload the code.
6. Place the robot on a flat surface and power it on.

---

## 🎯 Applications

* Robotics and Automation
* Control Systems Learning
* Embedded Systems Projects
* Educational Demonstrations
* PID Controller Implementation

---


## 🔮 Future Improvements

* Bluetooth/Wi-Fi remote control
* Mobile application support
* Obstacle avoidance using ultrasonic sensors
* Encoder-based speed control
* Kalman/Complementary filter optimization
* Autonomous navigation

---



## 👩‍💻 Author

**Roushani Kumari**
