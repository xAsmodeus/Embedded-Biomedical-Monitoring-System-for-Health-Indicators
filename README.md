<h1 align="center"> Embedded Biomedical Monitoring System for Health Indicators </h1>

---

## 📚 Table of Contents
- [Overview](#overview)
- [Digital Components](#digitalcomponents)
- [Tools & Technologies](#tools-technologies)
- [Licence](#licence)

--- 

## 🔍 Overview

The idea was to create a biomedical system that measures 3 values: Body Temperature , Pulse and Oxygen. When it detects unusual values that could put a person in danger, the system warns the user with special components such as the LED light and the Buzzer. If the person is considered to be in danger the LED lights up and the buzzer sounds , as the display warns the user with "**CAUTION**" while providing the measured values. If, on the other hand, the user has normal values, the buzzer does not sound , the LED does not light and the display provides the message "**YOU ARE OKAY**".

|Indicator|Danger Condition|
| :--------------------- | :--------------------- | 
| **O2**| < 95% |
| **Body Temp**| < 36°C OR > 38 |
| **Pulse**| < 50 OR  > 130 |


- The following image shows the wiring and the placement of the digital components

<div align="center">
  <p>
      <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/0f81f10e-7414-4ed6-bb8f-27c7369b639e" />
  </p> </div>
  
---

## 🔧 Digital Components

|Type|Quantity |
| :--------------------- | :--------------------- | 
| **DS18B20**| 1 |
| **Potentiometer**| 2 |
| **LED**| 1 |
| **Buzzer**| 1 |

---

## 🛠️ Tools & Technologies

- **Language:** C++
- **Libraries:** ...
- **Platform:** Wokwi.com

---

## ⚖️ Licence
(empty for the moment)

---

