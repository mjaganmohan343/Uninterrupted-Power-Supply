# 3-Phase Uninterruptible Power Supply (UPS) Project

This repository contains the design, code, and supporting files for a 3-phase Uninterruptible Power Supply (UPS) system, developed under the guidance of **Professor Vijay A.S**.

---

## Table of Contents

- [Introduction](#introduction)
- [System Overview](#system-overview)
  - [UPS Basics](#ups-basics)
  - [Rectifier Stage](#rectifier-stage)
  - [3-Phase Inverter Stage](#3-phase-inverter-stage)
- [Block Diagram](#block-diagram)
- [Working Principle](#working-principle)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Credits](#credits)
- [License](#license)

---

## Introduction

An **Uninterruptible Power Supply (UPS)** is a crucial device that ensures uninterrupted power to critical loads in case of utility failure. The UPS bridges the gap between power outage and generator startup, or simply keeps sensitive loads running until power is restored. This project focuses on a **three-phase UPS**, which is essential for industrial and commercial applications requiring balanced, high-power three-phase loads.

---

## System Overview

### UPS Basics

A typical UPS consists of three core functional blocks:

1. **Rectifier** – converts AC to DC to charge the batteries  
2. **Battery bank** – stores energy  
3. **Inverter** – converts stored DC back to AC to power the load

### Rectifier Stage

The rectifier converts incoming three-phase AC power to DC, which charges the battery bank. Controlled rectifiers can also regulate the charging current and protect against input fluctuations.

### 3-Phase Inverter Stage

During a mains power failure, the inverter takes energy from the battery bank and regenerates a clean three-phase AC supply. Using semiconductor switches (e.g., IGBTs or MOSFETs) with PWM techniques, the inverter synthesizes a sinusoidal output waveform with minimal harmonic distortion.

---

## Block Diagram

*(Add your block diagram here)*

```markdown
![Block Diagram](images/block_diagram.png)


