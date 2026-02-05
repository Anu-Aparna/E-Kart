# ⚡ EKART – 3 kW Electric Go-Kart Powertrain & Transmission

**Team Arinna | AIMS Championship**

---

## 📌 Problem Statement

Designing an electric go-kart requires accurate **powertrain and transmission sizing** to achieve required speed, torque, and efficiency while operating within motor power limits.
This project focuses on the **calculation, design, and implementation of a 3 kW electric powertrain** suitable for competitive karting conditions.

---

## 🎯 Objectives

* Design a transmission system for a **3 kW BLDC motor**
* Achieve a target top speed of **60 km/h**
* Optimize gear ratio for torque and drivability
* Validate power requirements against resistive forces
* Implement a reliable chain–sprocket drive system

---

## 🧩 System Overview

The electric go-kart uses a **single-stage chain drive transmission** powered by a **3 kW BLDC motor**.
Power is transmitted from the motor sprocket to the rear axle sprocket, converting motor RPM into usable wheel torque while overcoming rolling resistance and aerodynamic drag.

---

## 🔧 Vehicle & Design Parameters

| Parameter                            | Value          |
| ------------------------------------ | -------------- |
| Total Weight                         | 200 kg         |
| Target Top Speed                     | 60 km/h        |
| Motor Rated Power                    | **3 kW**       |
| Motor Speed                          | 2600 ± 100 RPM |
| Rolling Resistance Coefficient (Crr) | 0.02           |
| Drag Coefficient (Cd)                | 0.6            |
| Frontal Area                         | 1.125 m²       |
| Track Surface                        | Tar / Asphalt  |

---

## ⚙️ Powertrain Calculations

### Rolling Resistance Force

[
F_{rr} = C_{rr} \times m \times g
]
[
F_{rr} = 0.02 \times 200 \times 9.81 = 39.24\ \text{N}
]

### Aerodynamic Drag Force

[
F_d = 0.5 \times \rho \times C_d \times A \times v^2
]
[
F_d = 112.044\ \text{N}
]

### Total Power Required

[
P = (F_{rr} + F_d) \times v
]
[
P = 2521.83\ \text{W}
]

✅ **3 kW motor satisfies the power requirement**

---

## 🔁 RPM & Gear Ratio

| Parameter          | Value    |
| ------------------ | -------- |
| Required Wheel RPM | 1140 RPM |
| Motor RPM          | 2600 RPM |
| Velocity Ratio     | ≈ 2.0    |

---

## ⚙️ Torque Calculation

| Parameter            | Value        |
| -------------------- | ------------ |
| Motor Torque (Input) | 11.01 Nm     |
| Output Torque        | **22.02 Nm** |

---

## ⛓ Chain Drive Specification

| Component         | Specification |
| ----------------- | ------------- |
| Chain Type        | 08B-1 / R1278 |
| Chain Pitch       | 12.7 mm       |
| Driver Sprocket   | 13 teeth      |
| Driven Sprocket   | 26 teeth      |
| Centre Distance   | 280 mm        |
| Sprocket Material | Mild Steel    |
| Chain Material    | Mild Steel    |

---

## 🛠 Transmission Type

* **Single-speed chain drive**
* Horizontal motor mounting
* Rear axle driven configuration

---

## 📊 Results

* Required speed achieved within motor limits
* Smooth torque delivery across operating range
* Reliable chain drive under test conditions
* System met AIMS Championship performance requirements

---

## ⚠️ Limitations

* No regenerative braking
* Single-speed transmission limits optimization at varied speeds
* Manual tension adjustment required

---

## 🔮 Future Improvements

* Multi-stage or CVT transmission
* Lightweight sprocket materials
* Thermal analysis of motor under load
* Regenerative braking integration

---


## 👤 My Role

* Transmission system design
* Powertrain and resistance calculations
* Gear ratio and chain selection
* Assembly validation and testing
* Technical documentation

