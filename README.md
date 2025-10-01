# LEGO DOE Project 🚗📊

**Team 102 – SCM 517, W. P. Carey School of Business (MSBA Program)**

## 📌 Overview
This project applies **Design of Experiments (DOE)** methodology to optimize the performance of a LEGO race car. Using a factorial experimental design, we tested how factors such as wheel base, axle base, wheel size, and weight distribution influence the **distance traveled down a 30° ramp**.

By blending creativity with statistical rigor, this project highlights how DOE principles can be applied to real-world engineering and business analytics problems.

---

## 🎯 Objective
- **Primary Goal**: Design and optimize a LEGO race car capable of traveling the maximum distance down a ramp.
- **Constraints**:
  - Only LEGO blocks provided in the kit were used.
  - Each design required a windshield and steering wheel.
  - Cost considerations were incorporated using the Bill of Materials.

---

## 🧩 Experimental Setup
- **Ramp Specifications**: Height = 15 cm, Length = 30 cm, Angle = 30°
- **Factors and Levels**:

| Factor              | Levels Tested       |
|---------------------|---------------------|
| **Wheel Base**      | 3.5 cm, 5.0 cm      |
| **Axle Base**       | 1.5 cm, 3.4 cm      |
| **Wheel Size**      | Small, Large        |
| **Weight Distribution** | Front, Back   |

- **Response Variable**: Distance traveled (cm)
- **Replication**: Each of the 16 design combinations was tested 3 times (full factorial design = 48 trials).

---

## 🔬 Methodology
- **DOE Approach**: Full Factorial Design (2⁴ = 16 combinations).
- **Software Used**: Minitab for statistical analysis and visualization.
- **Analysis Performed**:
  - Main effects analysis
  - Two-way and three-way interactions
  - Model diagnostics (R², Adjusted R², Predicted R²)
  - Outlier detection

---

## 📊 Results & Key Insights
- **Significant Factors**:
  - **Axle Base**: Narrower axle base (1.5 cm) improved performance by reducing friction.
  - **Weight Distribution**: Front-weighted designs consistently outperformed back-weighted ones (stability).
  - **Wheel Size**: Smaller wheels performed better, though effect size was minimal.

- **Interaction Effects**:
  - Strong interaction between **Wheel Base × Axle Base**.
  - Three-way interactions (**Wheel Base × Weight Distribution × Axle Base**) significantly impacted performance.

- **Model Performance**:
  - R² = **87.49%**
  - Adjusted R² = **81.63%**
  - Prediction R² = **71.85%**
  - No multicollinearity issues (VIF = 1.00).
