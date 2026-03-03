# Scanning Probe Microscopy — Python Notebooks (Google Colab)

This repository contains interactive Python notebooks accompanying the textbook  
**Scanning Probe Microscopy — From Fundamentals to Quantitative Nanomechanics and Single-Cell Analysis**.

The notebooks translate textbook concepts into reproducible simulations, parameter studies, and visualization tools.

Each notebook:

- is self-contained,
- runs directly in Google Colab (no local installation required),
- includes conceptual reminders, parameter exploration, and sanity checks.

---

## Structure

### Part I — Foundations of SPM

#### Notebook 1 — Force–Deflection and Noise Simulator  
(Chapter 1: AFM as a Force Sensor)

Concepts:
- Hooke’s law in AFM
- nN–µN force regimes
- Thermal noise intuition

Outputs:
- Force vs deflection plots
- Noise estimates
- Order-of-magnitude reasoning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch01_force_sensor/SPM_Ch01_Notebook01_ForceDeflection_Noise.ipynb
)

---

#### Notebook 2 — AFM Force–Distance Simulation  
(Chapter 2: Tip–Sample Interactions)

Concepts:
- Lennard–Jones interaction
- Jump-to-contact instability
- Hertz contact mechanics
- JKR and DMT adhesive models
- Tabor parameter
- Hysteresis and energy dissipation

Outputs:
- Approach/retraction force–distance curves
- Pull-off force
- Young’s modulus extraction
- Dissipated energy estimation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch02_tip_sample_interactions/AFM_Force_Distance_LJ_Hertz_Adhesion.ipynb
)

---

## License

MIT License (see `LICENSE`).
