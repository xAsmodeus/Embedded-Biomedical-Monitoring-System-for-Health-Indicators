<h1 align="center"> Embedded Biomedical Monitoring System for Health Biomarkers </h1>

---

## 📚 Table of Contents
- [Overview](#overview)
- [Wiring & Installation](#wiringinstallation)
- [Results](#results)
- [Tools & Technologies](#tools-technologies)
- [Licence](#licence)

--- 

## 🔍 Overview

A biomedical system that measures 3 values: Body Temperature , Pulse and Oxygen. When it detects unusual values that could put a person in danger, the system warns the user with special components such as the LED light and the Buzzer. If the person is considered to be in danger the LED lights up and the buzzer sounds , as the display warns the user with "**CAUTION**" while providing the measured values. If, on the other hand, the user has normal values, the buzzer does not sound , the LED does not light and the display provides the message "**YOU ARE OKAY**".

|Indicator|Danger Condition|
| :--------------------- | :--------------------- | 
| **O2**| < 95% |
| **Body Temp**| < 36°C OR > 38 |
| **Pulse**| < 50 OR  > 130 |

|Type|Quantity |
| :--------------------- | :--------------------- | 
| **DS18B20**| 1 |
| **Potentiometer**| 2 |
| **LED**| 1 |
| **Buzzer**| 1 |

---

## ⚙️ Wiring & Installation

<div align="center">
  <p>
      <img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/0f81f10e-7414-4ed6-bb8f-27c7369b639e" />
  </p> </div>

---

## 📊 Results

Normal Results

<div align="center">
  <p>
      <img width="700" height="800" alt="normal_results" src="https://github.com/user-attachments/assets/55c3557d-889c-43ae-8b5f-40935371065c"/>
  </p> </div>

Abnormal Results

<div align="center">
  <p>
      <img width="700" height="800" alt="abnormal_results" src="https://github.com/user-attachments/assets/6ce9ca5e-8273-43ee-b3dd-5b3b9b8a768f" />
  </p> </div>
  
---

## 🛠️ Tools & Technologies

- **Language:** C++
- **Libraries:** DallasTemperature, OneWire
- **Platform:** Wokwi.com

---

## ⚖️ Licence
See the [Licence](LICENCE.md/) 
