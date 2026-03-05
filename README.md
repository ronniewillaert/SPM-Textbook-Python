# Scanning Probe Microscopy — Python Notebooks (Google Colab)

Interactive Python notebooks accompanying the textbook

**Scanning Probe Microscopy — From Fundamentals to Quantitative Nanomechanics and Single-Cell Analysis**

These notebooks translate key concepts from the textbook into **reproducible simulations, parameter exploration tools, and visualization exercises**.

The notebooks run directly in **Google Colab**, requiring **no local installation**.

---

## Features

Each notebook is a standalone executable learning module including:

• conceptual reminders  
• parameterized physical models  
• interactive exploration with sliders  
• visualization of nanoscale phenomena  
• unit checks and order-of-magnitude estimates

---

# Notebook Structure

## Part I — Foundations of Scanning Probe Microscopy

### Notebook 1 — Force–Deflection and Noise Simulator  
*(Chapter 1: AFM as a Force Sensor)*

Concepts:

- Hooke's law in AFM
- Force sensitivity
- Thermal noise of cantilevers

Outputs:

- Force–deflection plots
- Thermal noise estimation
- Order-of-magnitude reasoning

▶ **Run in Colab**

https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch01_force_sensor/SPM_Ch01_Notebook01_ForceDeflection_Noise.ipynb

---

### Notebook 2 — AFM Force–Distance Simulation  
*(Chapter 2: Tip–Sample Interactions)*

Concepts:

- Lennard–Jones interaction
- Jump-to-contact instability
- Hertz contact mechanics
- JKR and DMT adhesion models
- Tabor parameter
- Hysteresis and energy dissipation

Outputs:

- Approach/retraction force–distance curves
- Pull-off force
- Young's modulus extraction
- Dissipated energy estimation

▶ **Run in Colab**

https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch02_tip_sample_interactions/AFM_Force_Distance_LJ_Hertz_Adhesion.ipynb

---

### Notebook 3 — AFM Instrumentation Simulator  
*(Chapter 3: AFM Instrumentation and Detection Systems)*

Concepts:

- Cantilever force–deflection behaviour
- Optical beam deflection (optical lever)
- Thermal noise of AFM cantilevers
- Sensitivity of optical detection

Outputs:

- Force–deflection simulations
- Optical lever sensitivity analysis
- Thermal noise simulations

▶ **Run in Colab**

https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch03_afm_instrumentation/SPM_Ch3_AFM_Instrumentation_Python_Exercises.ipynb

---

## Repository Structure

```
SPM-Textbook-Python
│
├── binder
│   └── requirements.txt
│
├── notebooks
│   ├── part-01-foundations
│   │   ├── ch01_force_sensor
│   │   │   ├── SPM_Ch01_Notebook01_ForceDeflection_Noise.ipynb
│   │   │   └── README.md
│   │   │
│   │   ├── ch02_tip_sample_interactions
│   │   │   ├── AFM_Force_Distance_LJ_Hertz_Adhesion.ipynb
│   │   │   └── README.md
│   │   │
│   │   └── ch03_afm_instrumentation
│   │       ├── SPM_Ch3_AFM_Instrumentation_Python_Exercises.ipynb
│   │       └── README.md
│   │
│   ├── utils
│   └── README.md
│
├── LICENSE
├── CITATION.cff
└── README.md
```
