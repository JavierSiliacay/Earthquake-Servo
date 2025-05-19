# Arduino Earthquake Simulator

This project simulates earthquake shaking using a servo motor. The shaking intensity is controlled by a potentiometer, allowing users to adjust the delay between servo movements. The system outputs the intensity delay in milliseconds via the Serial Monitor.

## 🔧 Hardware Requirements

- Arduino Uno (or compatible)
- Servo Motor (e.g., SG90)
- Potentiometer
- Jumper Wires
- Breadboard
- USB Cable for programming and power

## ⚙️ How It Works

- A potentiometer connected to pin `A0` reads the analog value (0–1023).
- This value is mapped to a delay time between 169 ms and 1000 ms.
- A servo motor attached to pin `9` swings between 0° and 180° based on the delay.
- Serial output displays the mapped delay time for real-time feedback.

## 🧠 Educational Purpose

This project is designed for classroom demos or science exhibits to simulate how earthquakes vary in intensity and speed. Turning the knob changes how fast the servo "shakes," mimicking light to strong quakes.

## 📦 Libraries Used

- `Servo.h` (included with Arduino IDE)

