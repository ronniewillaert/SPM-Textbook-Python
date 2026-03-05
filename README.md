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

## Chapter 1 — AFM as a Force Sensor

Concepts:

- Hooke's law in AFM
- Thermal noise of cantilevers
- Force–deflection sensitivity

Outputs:

- Force vs deflection plots
- Thermal noise estimation
- Order-of-magnitude reasoning

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
