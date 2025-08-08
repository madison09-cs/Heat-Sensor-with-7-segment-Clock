# 🌡️ Heat Sensor with 7-Segment Clock Display

This Arduino project combines a **temperature sensor**, **RGB LED**, **piezo buzzer**, and a **7-segment display** to create an interactive system that monitors temperature, alerts users visually and audibly, and displays output in real time. It’s a fun and practical introduction to working with sensors, visual indicators, and digital displays.

---

## 📝 Description

The **Heat Sensor with 7-Segment Clock** project is designed to:
- Detect temperature using a **temperature sensor**
- Display temperature or timing on a **7-segment display**
- Flash RGB LED colors based on heat levels
- Sound a **piezo buzzer** as an alert when the temperature exceeds a defined threshold

This project demonstrates how real-world systems provide **visual, numeric, and audible feedback** in response to changing environmental conditions—just like basic HVAC or fire alert systems.

---

## 🔧 Components Used

| Component                   | Quantity |
|-----------------------------|----------|
| Arduino Uno R3              | 1        |
| Breadboard                  | 1        |
| Jumper Wires / Cables       | Several  |
| USB Cable (for Arduino IDE) | 1        |
| Temperature Sensor (e.g., TMP36) | 1   |
| Piezo Buzzer                | 1        |
| RGB LED                     | 1        |
| 220Ω Resistors              | 3        |
| 7-Segment Clock Display     | 1        |

---

## 🚀 Installation & Setup

1. **Connect the Temperature Sensor**:
   - VCC → 5V
   - GND → GND
   - Output → Analog Pin A0

2. **Wire the RGB LED**:
   - Red → Digital Pin 9 (via 220Ω resistor)
   - Green → Digital Pin 10 (via 220Ω resistor)
   - Blue → Digital Pin 11 (via 220Ω resistor)
   - Common cathode → GND

3. **Connect the Piezo Buzzer**:
   - Positive lead → Digital Pin 8
   - Negative lead → GND

4. **Connect the 7-Segment Display**:
   - Connect segments A–G and DP to digital pins
   - Connect common cathode or anode accordingly
   - Use current-limiting resistors as needed

5. **Upload Code**:
   - Open Arduino IDE
   - Connect the Arduino Uno via USB
   - Upload your sketch (including logic for reading the sensor, controlling RGB LED, buzzer, and display)

---

## ⚙️ How It Works

- The **temperature sensor** continuously reads ambient heat levels.
- If the temperature exceeds a threshold (e.g., 80°F or ~27°C):
  - The **RGB LED** flashes red.
  - The **piezo buzzer** sounds an alarm.
- The **7-segment display** shows either the current temperature or operates as a digital timer or clock.
- The RGB LED cycles through colors when the temperature is normal, adding a visual mood lighting effect.

This project offers a compact, multi-output interaction system using sensory and display technology.

---

## 💼 Portfolio

Check out more of my Arduino projects and documentation:  
🔗 [My Portfolio](https://sites.google.com/d/1kRYFgoPpI5KiRHlfU4u9C--i8z4OA6I5/p/1_ZLDAirpPNf5aijgyz-LQdDFrC5D1Gd2/edit)

---

## 🔬 Simulation

Try the project virtually with Tinkercad:  
▶️ [Tinkercad - Heat Sensor with Clock](https://www.tinkercad.com/things/kiKuaBQDfmm-heat-sensor-with-clock)

---

## 🙌 Credits

- Created by **[Madison Diggs]**
- Built using **Arduino Uno R3**
- Inspired by real-world HVAC, safety, and display systems

---

## 📄 License

This project is open-source and licensed under the Code in the Schools.

---
