# Electronics II - Design, SPICE Simulation & Laboratory Analysis

This repository contains the complete project for the **Electronics II** course (2023). The work integrates rigorous theoretical calculations, SPICE simulations, and experimental validation for complex analog circuits.

## 🚀 Project Overview
The project covers the design and analysis of high-performance amplifiers and oscillators, focusing on DC biasing, AC gain, and frequency response.

## 🛠 Tech Stack
* **Simulation:** SPICE (Analysis of DC, Transient, and AC Sweep)
* **Components:** BJT (BC238), JFET (J2N3819), Op-Amp (μA741)
* **Documentation:** Technical Report with circuit schematics and waveforms

## 📋 Key Modules Analyzed

### 1. Differential Amplifier Stage
* **Theoretical Analysis:** Calculation of operating points ($I_{Cq}$, $V_{CEq}$) and voltage gain.
* **SPICE Validation:** Comparison of theoretical values with simulated DC sweeps and transfer characteristics.

### 2. High-Gain Cascode Amplifier
* Combined **JFET (Common Source)** and **BJT (Common Base)** configuration.
* Detailed analysis of input/output impedance and bandwidth.
* Simulation of frequency response to identify cut-off frequencies.

### 3. Feedback Amplifiers
* Study of **Voltage-Series** and **Current-Parallel** feedback topologies.
* Quantifying the impact of negative feedback on gain stability and signal distortion.

### 4. Operational Amplifier (μA741) Applications
* **Schmitt Trigger:** Designing for specific hysteresis thresholds ($V_{UT}$, $V_{LT}$).
* **Pulse Generation:** Implementation of astable multivibrators for square-wave generation.

### 5. Sinusoidal Oscillators
* **Phase-Shift & Wien Bridge Oscillators:** Setting the barkhausen criterion for stable oscillations.
* Analysis of frequency accuracy between SPICE simulations and laboratory measurements.

## 📂 Repository Structure
* `/docs`: Final laboratory report (PDF) and assignment descriptions.
* `/simulations`: SPICE circuit files (.asc / .cir / .net).
* `/images`: Waveform captures (Bode plots, Oscilloscope screenshots).

## 🎓 Academic Info
* **Institution:** Aristotle University of Thessaloniki (AUTh)
* **Course:** Electronics II (2023)
* **Department:** Electrical and Computer Engineering
