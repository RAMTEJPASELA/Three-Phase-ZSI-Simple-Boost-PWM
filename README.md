# ⚡ Operation & Analysis of Three-Phase Z-Source Inverter Using Simple Boost PWM Control in MATLAB Simulink

**Pasela Ramtej** | Department of Electrical Engineering, Andhra University  
**Project Trainee – URSC, ISRO**

---

## Overview
This repository presents the design, simulation, and detailed analysis of a **Three-Phase Z-Source Inverter (ZSI)** employing a **Simple Boost PWM** control strategy in **MATLAB Simulink**. The system targets a line-to-line RMS output of **230 V** with efficiencies exceeding **95%**, and offers insights for applications in **renewable energy**, **electric vehicles**, and **industrial power electronics**.

**Key Features:**
- **Buck–Boost Capability:** Z-source network allows both voltage stepping-up and stepping-down without external converters.
- **High Efficiency:** Achieves >95% efficiency across multiple operating points.
- **Robust PWM Control:** Implements Simple Boost Control (SBC) with triangular-carrier PWM for reliable shoot-through management.

---

## Table of Contents
1. [Circuit Topology & Simulink Model](#circuit-topology--simulink-model)  
2. [Case Studies](#case-studies)  
   - [Case 1: M = 0.86, VB = 310 V](#case-1-m--086-vb--310-v)  
   - [Case 2: M = 0.90, VB = 333.8 V](#case-2-m--090-vb--3338-v)  
   - [Case 3: M = 0.94, VB = 350 V](#case-3-m--094-vb--350-v)  
3. [Simulation Results](#simulation-results)  
4. [Contact & Acknowledgements](#contact--acknowledgements)

---

## Circuit Topology & Simulink Model

### Circuit Topology
![Circuit Topology](https://github.com/user-attachments/assets/269810e7-b1ae-4333-95c7-367031e08e7c)

### Power Circuit in MATLAB Simulink
![Power Circuit in MATLAB Simulink](https://github.com/user-attachments/assets/bb710003-6a12-432d-b632-b9201a2b321b)

### Control Circuit in MATLAB Simulink
![Control Circuit in MATLAB Simulink](https://github.com/user-attachments/assets/2592eef8-cc3f-4ff8-bfaf-fe37303d75b1)

---

## Case Studies
We evaluated the inverter performance under three modulation indices. All simulations ran for 0.1 s with a discrete step of 50 µs and a switching frequency of 10 kHz.

### Case 1: M = 0.86, VB = 310 V
| Parameter                              | Expected | Simulated |
|----------------------------------------|:--------:|:---------:|
| Modulation Index (M)                   | 0.86     | 0.86      |
| Shoot‑Through Duty (D<sub>0</sub>)     | 0.14     | 0.14      |
| Boost Factor (B)                       | 1.38     | 1.38      |
| V<sub>LL,rms</sub> (230 V)             | 230 V    | 228.7 V   |
| I<sub>out</sub> (1.25 A)               | 1.25 A   | 1.24 A    |
| Efficiency                             | 100%     | 98.7%     |

### Case 2: M = 0.90, VB = 333.8 V
| Parameter                              | Expected | Simulated |
|----------------------------------------|:--------:|:---------:|
| Modulation Index (M)                   | 0.90     | 0.90      |
| Shoot‑Through Duty (D<sub>0</sub>)     | 0.10     | 0.10      |
| Boost Factor (B)                       | 1.25     | 1.25      |
| V<sub>LL,rms</sub> (230 V)             | 230 V    | 229.7 V   |
| I<sub>out</sub> (1.25 A)               | 1.25 A   | 1.25 A    |
| Efficiency                             | 100%     | 99.5%     |

### Case 3: M = 0.94, VB = 350 V
| Parameter                              | Expected | Simulated |
|----------------------------------------|:--------:|:---------:|
| Modulation Index (M)                   | 0.94     | 0.94      |
| Shoot‑Through Duty (D<sub>0</sub>)     | 0.06     | 0.06      |
| Boost Factor (B)                       | 1.13     | 1.13      |
| V<sub>LL,rms</sub> (230 V)             | 230 V    | 229.5 V   |
| I<sub>out</sub> (1.25 A)               | 1.25 A   | 1.24 A    |
| Efficiency                             | 100%     | 99.3%     |

---

## Simulation Results

### Output Line-to-Line Voltage (Case 1)
<img src="assets/v_line_line_case1.png" alt="Line-to-Line Voltage Case 1" width="600"/>

### Output Phase-to-Neutral Voltage (Case 1)
<img src="assets/v_phase_neutral_case1.png" alt="Phase-to-Neutral Voltage Case 1" width="600"/>

### Output Line-to-Line Current (Case 1)
<img src="assets/i_line_line_case1.png" alt="Line-to-Line Current Case 1" width="600"/>

---

## Contact & Acknowledgements
**Pasela Ramtej** – Project Trainee, URSC, ISRO  
Department of Electrical Engineering, Andhra University  

- 📧 [ramtejpasela@gmail.com](mailto:ramtejpasela@gmail.com)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/paselaramtej)

_Thanks to Dr. N. Kumaresan (NIT Tiruchirappalli) and colleagues for their guidance and support._

_Last updated: April 2025_
