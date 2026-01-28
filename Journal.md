# Project Journal – Ultrasensitive Electroscope

This journal documents my progress, decisions, experiments, and learnings while building an ultrasensitive electroscope.

---

# Day 1 – Project Idea & Research

## Thursday, 8 January 2025

**What I did**
I spent this day researching how traditional electroscopes work and why they struggle with detecting very weak electric charges. I also explored different ultrasensitive electroscope designs and the physics principles behind them, focusing on what actually improves sensitivity rather than just basic functionality.


**What I learned**
I learned that sensitivity depends heavily on factors like the mass of moving parts, insulation quality, and even small air currents. I also realized that charge leakage is one of the biggest limitations in high-sensitivity electroscopes.

**Time Spent:** 2 hours

---

# Day 2 – Design & Materials

## Friday, 9 January 2025

**What I did**
I reviewed the previous version of the electroscope and identified its main issues, including low accuracy, an inefficient LCD, and high noise. After that, I selected better insulating materials to reduce charge loss and sketched a new mechanical layout aimed at improving sensitivity.

**Challenges**
The biggest challenge was balancing mechanical stability with sensitivity. Making the system more stable usually meant adding mass, which directly reduced responsiveness.

**What I learned**
Even very small increases in mass can significantly reduce how responsive the electroscope is.

**Time Spent:** 2 hours

---

# Day 3 – Development

## Saturday, 10 January 2025

**What I did**
I focused on the electronics side of the project by researching operational amplifiers, especially rail-to-rail op-amps, and why they are important for low-signal measurements. I then prepared a complete materials list and bought the required components, including an ATmega32P, breadboards, jumpers, resistors, ceramic capacitors, two 9V batteries with holders, a 16×2 LCD, a GS6002-SRNCP6002 op-amp, and a step-down module.

**Why**
The previous op-amp was not rail-to-rail, which caused unstable and random readings. The LCD was also not suitable for displaying charge values every 0.5 seconds, making real-time monitoring difficult.

**Time Spent:** 4 hours

---

# Day 4 – Designing the New Circuit

## Sunday, 11 January 2025

**What I did**
I designed a new schematic diagram using the updated components and built the circuit physically. After assembling the prototype, I tested it multiple times to evaluate performance.![6f78edd1-29df-4540-889e-dfddaa51c5fd](https://github.com/user-attachments/assets/03f2d2a1-5978-49e7-896b-456a4067c478)

![8c7c090f-abfa-444f-8821-e1cd19545282](https://github.com/user-attachments/assets/341ab98f-9bbd-4e7f-93ae-332ecca96c25)

**Results**
The new design showed a clear increase in sensitivity and much more stable readings. However, the prototype was still strongly affected by environmental conditions such as air movement, humidity, and nearby electronics.

**Time Spent:** 6 hours

---

# Day 5 – Improving Accuracy and Environmental Stability

## Monday, 12 January 2025

**What I did**
I researched different isolation methods and materials that could reduce environmental interference. Based on this, I designed a 3D model of an isolation box made from acrylic sheets to protect the sensitive components. I also explored different probe designs and built a new double circular sandwich-style probe using aluminum foil.

**Results**
After these changes, the electroscope showed higher sensitivity and noticeably more stable readings under the same environmental conditions.

**Time Spent:** 4 hours
