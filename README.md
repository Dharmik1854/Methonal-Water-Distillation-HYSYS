# Methanol-Water Distillation Process Simulation 🏭

## 📌 Executive Summary
This repository contains the complete process design, thermodynamic simulation, and mathematical validation of a binary distillation column separating a Methanol-Water mixture. The model was developed using **Aspen HYSYS V10/V11**, applying the **NRTL (Non-Random Two-Liquid)** property package to accurately predict vapor-liquid equilibrium (VLE) for this highly non-ideal mixture.

## ⚙️ Process Specifications & Design Parameters
* **Thermodynamic Model:** NRTL
* **Feed Conditions:** Equimolar mixture (50% Methanol, 50% Water) at 71.5°C and 1 atm.
* **Feed Flow Rate:** 25 kmol/h (approx. 625 kg/h)
* **Target Purity:** 95% Methanol recovery in the distillate.
* **Reflux Ratio:** 2.5 (Optimized for energy efficiency)
* **Column Hardware:** 26 Actual Trays (assuming 70% tray efficiency) corresponding to 18 Theoretical Stages.

## 📊 Energy Profile & Key Performance Indicators
Through rigorous Degrees of Freedom (DOF) control and specification targeting, the following energy duties were achieved:
| Parameter | Value | Unit |
| :--- | :--- | :--- |
| **Condenser Duty (Qc)** | ~427 | kW |
| **Reboiler Duty (Qr)** | ~494 | kW |
| **Distillate Flow** | 12.50 | kmol/h |
| **Bottoms Flow** | 12.50 | kmol/h |

## 📁 Repository Structure
1. **`Simulation/`**: Contains the native Aspen HYSYS `.hsc` file.
2. **`Calculations/`**: Contains the manual step-by-step mathematical validation (Overall Mass Balance, Component Balance, and Tray Efficiency calculations).
3. **`Images/`**: Process Flow Diagrams (PFD) and Stage-by-Stage Temperature/Composition profiles.

## 🛠️ Engineering Value
This project demonstrates strong fundamental knowledge of **Chemical Process Industries**, mastery over **Process Equipment Design**, and the practical ability to translate theoretical thermodynamic equations into functional industrial plant simulations.
