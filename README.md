# Scanning Probe Microscopy — Python Notebooks (Google Colab)

This repository contains interactive Python notebooks accompanying the textbook:

**Scanning Probe Microscopy — From Fundamentals to Quantitative Nanomechanics and Single-Cell Analysis**

The notebooks translate textbook concepts into **interactive simulations, parameter exploration, and visualization tools**.

Each notebook:

- runs directly in **Google Colab**
- requires **no local installation**
- includes **concept reminders**
- allows **interactive parameter exploration**

---

# Part I — Foundations of SPM

### Chapter 1 — AFM as a Force Sensor

**Exercise 1.8.3.1 — Force–Deflection, Thermal Noise, and Nanoscale Physics in AFM**

This notebook integrates the key quantitative concepts from Chapter 1 into seven interactive simulations. Students adjust parameters via sliders and immediately observe the effect on force magnitude, resolution limits, tunneling current, thermal noise, and signal-to-noise ratio.

Topics:

- **Hooke's Law in AFM** — Interactive force calculator with force regime classification (Section 1.5)
- **Abbe's Diffraction Limit** — Why SPM bypasses wavelength-based resolution (Section 1.2)
- **STM Tunneling Current** — Exponential distance sensitivity enabling atomic resolution (Section 1.3)
- **Thermal Noise and the Sensitivity–Noise Trade-Off** — Equipartition theorem and cantilever selection (Section 1.5)
- **Hertz Contact Model** — Estimating cell indentation forces with adjustable modulus, tip radius, and depth (Section 1.6)
- **Sanity-Check Dashboard** — Order-of-magnitude reasoning against the physical reference table (Table 1.3)
- **Engineering Insight** — Resolution vs reliability: why higher resolution does not imply higher mechanical accuracy

Outputs:

- Force vs deflection plots for multiple cantilever stiffnesses
- Resolution comparison across microscopy techniques (AFM, STED, SIM, optical)
- Tunneling current decay curves (linear and log scale)
- Thermal deflection, force noise, and SNR as a function of spring constant
- Hertz indentation force vs depth and Young's modulus
- Sanity-check dashboard comparing computed, reported, and thermal forces
- Trade-off summary table (soft vs stiff cantilevers)

**Launch notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch01_force_sensor/SPM_Ch01_Notebook01_ForceDeflection_Noise.ipynb)

---

## Chapter 2 — Tip–Sample Interactions

Concepts:

- Lennard–Jones interaction
- Jump-to-contact instability
- Hertz contact mechanics
- JKR and DMT adhesion models
- Tabor parameter

Outputs:

- Force–distance curves
- Pull-off force
- Young’s modulus extraction
- Energy dissipation

**Launch notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch02_tip_sample_interactions/AFM_Force_Distance_LJ_Hertz_Adhesion.ipynb)

---

## Chapter 3 — AFM Instrumentation and Detection

Concepts:

- Cantilever force–deflection behaviour
- Optical beam deflection (optical lever)
- Thermal noise of AFM cantilevers
- Sensitivity of optical detection

Outputs:

- Force–deflection simulations
- Optical lever sensitivity analysis
- Thermal noise simulations

**Launch notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch03_afm_instrumentation/SPM_Ch3_AFM_Instrumentation_Python_Exercises.ipynb)

---

## Chapter 4 — AFM Scanning Simulator (Raster Scan + Feedback Artifacts)

Concepts:
- Raster scanning (fast/slow axis), pixel dwell time
- Feedback bandwidth and tracking error
- Imaging artifacts: lag, edge rounding, overshoot, drift
- Tip-size effects (proxy)

Outputs:
- True surface vs measured image
- Tracking error map
- Interactive “artifact laboratory” via sliders

---

**Launch notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch04_afm_scanning_simulator/SPM_Ch4_AFM_Scanning_Simulator.ipynb)


# Repository Structure

<!-- repo-tree-start -->

```
.
├── CITATION.cff
├── LICENSE
├── README.md
├── binder
│   └── requirements.txt
└── notebooks
    ├── README.md
    ├── part-01-foundations
    │   ├── README.md
    │   ├── ch01_force_sensor
    │   │   ├── README.md
    │   │   └── SPM_Ch01_Notebook01_ForceDeflection_Noise.ipynb
    │   ├── ch02_tip_sample_interactions
    │   │   ├── AFM_Force_Distance_LJ_Hertz_Adhesion.ipynb
    │   │   └── README.md
    │   ├── ch03_afm_instrumentation
    │   │   ├── README.md
    │   │   └── SPM_Ch3_AFM_Instrumentation_Python_Exercises.ipynb
    │   └── ch04_afm_scanning_simulator
    │       ├── README.md
    │       └── SPM_Ch4_AFM_Scanning_Simulator.ipynb
    └── utils
        └── README.md

9 directories, 15 files
```
<!-- repo-tree-end -->

---

# How to use the notebooks

1. Click **Open in Colab**
2. Run the notebook cells sequentially
3. Modify parameters using sliders
4. Explore how AFM physics responds

The notebooks are designed as **interactive companions to the textbook**, not as standalone scripts.

---

# License

MIT License
