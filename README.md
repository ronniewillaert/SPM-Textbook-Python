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

**Exercise 2.8 — Force–Distance Curves: From Lennard-Jones to Adhesion Mechanics**

This notebook integrates the key quantitative concepts from Chapter 2 into eleven interactive simulations. Students adjust parameters via sliders and immediately observe the effect on interaction potentials, surface forces, contact mechanics, adhesion, and force–distance curve behaviour.

Topics:

- **Lennard-Jones Potential & Force** — Pair interaction between neutral atoms with adjustable well depth and equilibrium distance (Section 2.2)
- **Van der Waals Sphere–Plane Interaction** — Hamaker integration for macroscopic tip–surface forces with tuneable Hamaker constant and tip radius (Section 2.4)
- **Electrostatic Forces & Debye Screening** — Ion concentration and charge effects on screening length and double-layer forces (Section 2.4)
- **DLVO Theory** — Combined van der Waals attraction and electrostatic double-layer repulsion with energy barrier visualisation (Section 2.4)
- **Capillary Forces** — Humidity-dependent adhesion from meniscus formation between tip and surface (Section 2.5)
- **Jump-to-Contact Instability** — Cantilever stiffness vs interaction gradient, mechanical stability condition, and snap-in distance (Section 2.6)
- **Contact Mechanics: Hertz, JKR & DMT** — Elastic contact models with adhesion, force–indentation curves, and contact radius comparison (Section 2.7)
- **Tabor Parameter Classification** — Interactive mapping of material combinations onto the JKR–DMT spectrum (Section 2.7)
- **Complete Force–Distance Curve Simulation** — Full approach–retract cycle combining vdW forces, contact mechanics, adhesion hysteresis, and cantilever dynamics (Section 2.8)
- **Bell-Evans Model** — Loading-rate dependence of molecular rupture forces and bond energy landscape (Section 2.8)
- **Parameter Exploration** — How experimental choices (cantilever stiffness, tip radius, environment) affect measured force curves (Section 2.8)

Outputs:

- Lennard-Jones potential and force curves with tuneable parameters
- Sphere–plane van der Waals force vs distance for varying Hamaker constant and tip radius
- Debye screening length and electrostatic force profiles
- DLVO energy curves showing attractive/repulsive regimes and energy barriers
- Capillary force as a function of humidity, contact angle, and surface tension
- Jump-to-contact stability diagrams and snap-in distance predictions
- Hertz, JKR, and DMT force–indentation curves with contact radius comparison
- Tabor parameter classification map for common material combinations
- Simulated approach–retract force–distance curves with hysteresis
- Bell-Evans rupture force vs loading rate (linear and log scale)
- Parameter trade-off summary for experimental design

**Launch notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch02_tip_sample_interactions/AFM_Force_Distance_LJ_Hertz_Adhesion.ipynb)


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
