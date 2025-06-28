# 📗 Arduino Beginner Training Portfolio

Welcome to my Arduino Beginner Training Portfolio!  
This repository documents my hands-on learning journey in embedded electronics using the Arduino platform. I focused on understanding the core logic, syntax, and input/output operations by building practical hardware projects.

---

## 📅 Timeline & Topics Covered

| Date           | Focus Area               | Concepts Learned                                                                 |
|----------------|--------------------------|----------------------------------------------------------------------------------|
| 22nd June 2025 | Getting Started          | What is Arduino, IDE setup, differences between Uno, Nano, and ESP32            |
| 22nd June 2025 | Sketch Structure & Syntax | `setup()`, `loop()`, `pinMode()`, `digitalWrite()`, `delay()`, code comments    |
| 22nd June 2025 | LED Projects             | LED blinking patterns using digital pins, for loops, and custom delay timing    |
| 26th June 2025 | Servo Motor Control      | Joystick analog input, mapping to servo angle, live control loop logic          |
| 27th June 2025 | Flame Sensor + Buzzer    | Flame intensity detection, `tone()`/`noTone()` control based on analog values    |

---

## ✅ Projects Completed

### 🔦 Fade Simulation with Delay  
**Date:** 22nd June 2025  
**Goal:** Simulate fading LED brightness by reducing the blink delay in a loop  
**Tools Used:** `for` loop, `digitalWrite()`, dynamic `delay()`  
**What I Learned:**
- How `delay()` controls LED blinking rate and simulates brightness  
- `for` loop usage with descending step  
- Preventing bugs from overly fast or negative delay values  

---

### 🎮 Servo Motor Control via Joystick  
**Date:** 26th June 2025  
**Goal:** Use joystick module to control servo motor angle in real time  
**Tools Used:** `analogRead()`, `map()`, `myservo.write()`, serial monitor  
**What I Learned:**
- How to read analog voltage from joystick  
- Mapping joystick X-axis to servo angles (0°–160°)  
- Using the joystick’s switch state  
- Visual feedback via `Serial.print()`  

---

### 🔥 Flame Sensor Alarm with Buzzer  
**Date:** 27th June 2025  
**Goal:** Detect flame intensity and alert using buzzer tone  
**Tools Used:** Flame sensor (analog pin), `tone()`, `map()`, `Serial.println()`  
**What I Learned:**
- How flame sensors output analog values based on infrared light  
- Using `map()` to convert sensor values to pitch  
- Creating real-time alerts with dynamic buzzer tones  
- Threshold logic for turning alerts on/off  

---

## 💬 Reflection

> “Each project deepened my confidence in controlling real-world components through code. From blinking an LED to controlling a servo and reacting to fire — this journey is training me for my larger goal: designing intelligent, responsive embedded systems.”

---

📌 More advanced projects, including display modules, sensor fusion, and AI-on-Edge simulations, will be added as I progress.
