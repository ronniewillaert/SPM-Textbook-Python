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


---

# Chapter 3 — AFM Instrumentation and Detection Systems

## Exercise 3.9.3 — AFM Instrumentation: From Detection to Measurement

This notebook integrates the key instrumentation concepts from Chapter 3 into ten interactive simulations. Students adjust parameters via sliders and immediately observe the effect on cantilever mechanics, optical detection, piezoelectric scanning, feedback control, thermal noise, and force calibration.

Topics:

- **Cantilever Force–Deflection (Hooke's Law)** — Linear spring model of the AFM cantilever with tuneable stiffness and force sensitivity comparison (Section 3.2)
- **Optical Lever Amplification** — Geometric amplification of cantilever tilt into measurable laser spot displacement for different detector distances (Section 3.3)
- **Quadrant Photodiode Detection** — Gaussian laser spot on a four-segment detector with normalized differential signals for vertical and lateral force detection (Section 3.3)
- **Piezoelectric Scanner Displacement** — Voltage-to-displacement conversion for single-layer and stack actuators with tuneable piezo coefficient (Section 3.4)
- **Piezoelectric Hysteresis** — Forward and return displacement paths showing positioning errors from hysteresis in open-loop scanners (Section 3.4)
- **PI Feedback Control** — Proportional–Integral controller tracking a surface step feature with adjustable gains and scan speed (Section 3.5)
- **Feedback Bandwidth as Low-Pass Filter** — Spatial frequency analysis linking scan speed, feature wavelength, and maximum trackable frequency (Section 3.5)
- **Thermal Noise of AFM Cantilevers** — Equipartition theorem applied to cantilever fluctuations with minimum detectable force analysis (Section 3.6)
- **Deflection Sensitivity Calibration** — Complete voltage-to-deflection-to-force calibration chain with error propagation analysis (Section 3.7)
- **Cantilever Selection for Different Applications** — Parameter trade-off explorer comparing real commercial probes across biological, polymer, hard material, force spectroscopy, and high-speed imaging applications (Section 3.2, 3.6)

Outputs:

- Force–deflection curves comparing soft and stiff cantilevers
- Optical lever spot displacement vs tilt angle for varying detector distance
- Quadrant photodiode response curve showing linear detection range
- Piezoelectric displacement vs voltage for single-layer and stack actuators
- Hysteresis loop with positioning error quantification
- PI feedback step response for low, medium, and high gain settings
- Bandwidth diagram mapping feature frequency against scan speed
- Thermal noise histograms with theoretical Gaussian overlay and minimum detectable force
- Force curve calibration on hard surface with error propagation contour map
- Cantilever selection dashboard with sensitivity, noise, SNR, and application matching

**Launch notebook**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch03_afm_instrumentation/SPM_Ch3_AFM_Instrumentation_Python_Exercises.ipynb)

---
## Chapter 4 — AFM Imaging Modes: From Contact to High-Speed

### Exercise 4.6.4 — AFM Imaging Modes: Interactive Simulations

This notebook integrates key imaging mode concepts from Chapter 4 into ten interactive simulations. Students adjust parameters and observe effects on contact-mode tracking, cantilever dynamics, tapping-mode setpoint selection, phase contrast, FM-AFM frequency shifts, scanning artifacts, tip convolution, and nanomechanical mapping.

**Topics Covered:**

- **Contact Mode: Constant-Force vs Constant-Height** — Feedback tracking of surface topography with tuneable spring constant, setpoint, bandwidth, and scan speed (Section 4.1)
- **Driven Damped Harmonic Oscillator** — Cantilever resonance, Q-factor comparison in air versus liquid, and response time trade-offs (Section 4.2.1)
- **Tapping Mode Amplitude–Distance Curve** — Setpoint ratio selection (gentle vs aggressive), working distance, and interaction regime identification (Section 4.2.2)
- **Phase Imaging and Energy Dissipation** — Material contrast from phase lag, dissipation mapping with E_diss ∝ A·sin(φ), and amplitude dependence (Section 4.2.3)
- **FM-AFM Frequency Shift** — Force gradient detection from Lennard-Jones interaction, sensitivity analysis with cantilever stiffness and resonance frequency (Section 4.2.4)
- **AFM Modes on the Force–Distance Curve** — Mapping contact, tapping, and non-contact modes onto attractive and repulsive interaction regimes (Section 4.2)
- **Scanning Artifacts and Feedback Bandwidth** — Forward/backward scan comparison, edge rounding, scan-direction asymmetry, and bandwidth limitations (Section 4.4)
- **Tip Convolution and Geometric Broadening** — Lateral broadening formula w_measured ≈ w + 2√(2Rh), tip radius and feature height dependence (Section 4.4)
- **QI Mode and PeakForce Tapping** — Hertz model force curves, nanomechanical parameter extraction (stiffness, deformation, adhesion), and spatial mapping (Section 4.3)
- **AFM Mode Selection Decision Tool** — Interactive scoring and ranking of imaging modes based on sample stiffness, environment, measurement target, and adhesion (Section 4.5)

**Outputs:**

- Constant-force vs constant-height topography and deflection signals
- Amplitude and phase resonance curves comparing air and liquid environments
- Amplitude–distance curves with gentle and aggressive setpoint markers
- Phase contrast and energy dissipation maps for elastic vs viscoelastic materials
- Lennard-Jones potential, force, force gradient, and FM-AFM frequency shift curves
- Force–distance curve with contact, tapping, and non-contact operating regions marked
- Forward and backward scan lines with tracking error diagnostics
- Tip-convolved profiles with broadening vs tip radius and feature height plots
- Hertz force–indentation curves with spatial stiffness and deformation maps
- Mode selection ranking bar chart and property comparison radar

**Launch notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch04_afm_imaging_modes/SPM_Ch4_AFM_Imaging_Modes_Python_Exercises.ipynb)

---

## Chapter 5 — Force–Distance Curve Analysis

### Exercise 5.11.3 — Force–Distance Curve Analysis: Interactive Simulations

This notebook integrates key force–distance curve concepts from Chapter 5 into ten interactive simulations. Students adjust parameters and observe effects on curve shape, measurement chain calibration, contact mechanics model selection, parameter extraction, force mapping, and experimental design for biological samples.

**Topics Covered:**

- **Force–Distance Curve: Approach and Retraction** — Interaction regimes (I–VI), jump-to-contact, pull-off, and the effect of cantilever stiffness and adhesion on curve shape (Section 5.1)
- **The AFM Measurement Chain** — Conversion from raw photodiode voltage to force via sensitivity and spring constant calibration, with error propagation (Section 5.2)
- **Hysteresis and Energy Dissipation** — Trapezoidal integration of approach–retraction loop area, conservative vs dissipative contributions, and energy in kT units (Section 5.3)
- **Quantitative Parameter Extraction** — Adhesion force, work of adhesion, contact stiffness, energy dissipation, and indentation from a single force curve (Section 5.4)
- **Contact Point Detection** — Threshold vs ratio-of-variances (RoV) methods, and how contact-point uncertainty propagates into Young's modulus error (Section 5.6)
- **Hertz Model Fitting** — Sphere and cone tip geometries, noise effects, fit-range sensitivity, and residual analysis for extracting E* (Section 5.8)
- **Contact Mechanics Models: Hertz vs JKR vs DMT** — Tabor parameter–based model selection, adhesion regimes, and the impact of model choice on fitted modulus (Section 5.8)
- **Force Mapping** — From single curve to spatial property maps (topography, adhesion, modulus) on heterogeneous samples using force volume imaging (Section 5.7)
- **Bacterial Stiffness Measurement** — The 10% indentation rule, cantilever selection, z-piezo partitioning, and iterative measurement design for soft biological samples (Section 5.9)
- **Speed vs Information Trade-Off** — Sampling density, acquisition time, and precision comparison across Force-Volume, QI/fast force mapping, and PeakForce QNM modes (Section 5.7)

**Outputs:**

- Approach and retraction force–distance curves with labeled interaction regimes
- Four-step measurement chain (voltage → deflection → force → indentation) with calibration error
- Force–indentation hysteresis loops with dissipated energy shading
- Annotated force curves with extracted parameters and contact stiffness gradient
- Contact point detection comparison (threshold vs RoV) with E* error propagation
- Hertz model fits with residual plots for sphere and cone geometries
- Three-model overlay (Hertz/JKR/DMT) with Tabor parameter phase diagram
- Force volume maps (topography, adhesion, modulus) on a two-phase sample
- Bacterial indentation curves with z-piezo partition bar charts and pass/fail diagnostics
- Sampling density comparison histograms and acquisition time estimates

**Launch notebook**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch05_force_distance_curve_analysis/SPM_Ch5_Force_Distance_Curve_Python_Exercises.ipynb)

---

## Chapter 6 — Quantitative Nanomechanics

### Exercise 6.9.3 — Quantitative Nanomechanics: Interactive Simulations

This notebook integrates key contact-mechanics concepts from Chapter 6 into six interactive simulations. Students adjust parameters and observe effects on Hertz fitting, tip-geometry bias, adhesive contact regimes, substrate corrections, modulus mapping of heterogeneous samples, and the statistical comparison of cell populations under mechanical stimulation.

**Topics Covered:**

- **Hertz Model Fitting** — Synthetic force–indentation generation, noise, fit-range sensitivity, residual analysis, and the role of the Poisson ratio in extracting the effective Young's modulus E* (Section 6.1)
- **Tip Geometry: Hertz vs Sneddon** — Spherical vs conical tip force laws, log–log slope diagnostics, and the systematic bias of fitting with the wrong geometry (Sections 6.2 and 6.4)
- **Adhesion: Hertz vs JKR vs DMT** — Adhesive contact mechanics, pull-off force, and the Tabor parameter μ as a model-selection criterion across the JKR / transition / DMT regimes (Section 6.3)
- **Substrate Effects on Thin Samples** — Bottom-Effect Correction (BEC) for finite-thickness layers on rigid substrates, the χ = √(Rδ)/h scaling, and the validity of the 10 % indentation rule (Section 6.5)
- **Modulus Mapping of a Heterogeneous Sample** — Force-volume imaging on soft/stiff regions, per-pixel Hertz fitting, modulus map reconstruction, and contrast vs noise analysis (Section 6.7)
- **Biological Case Study: Control vs Stiffened Cells** — Log-normal cell-population sampling, Welch t-test on log-moduli, Mann–Whitney U test, and Cohen's d for mechanobiological comparisons (Section 6.7)

**Outputs:**

- Hertz fits with residual plots, parameter standard errors, and fit-range stability sweeps
- Hertz vs Sneddon comparison plots with log–log slope diagnostic and local exponent traces
- Three-model overlay (Hertz / JKR-like / DMT) on adhesive curves with Tabor regime map
- Thin-sample force curves with BEC stiffening factor and apparent E* vs δ_max bias plots
- Force-volume modulus maps with bimodal distribution histograms
- Control vs stiffened cell modulus distributions on log-scale box plots, with t-test and Mann–Whitney p-values and effect sizes (Cohen's d)

**Launch notebook**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronniewillaert/SPM-Textbook-Python/blob/main/notebooks/part-01-foundations/ch06_quantitative_nanomechanics/SPM_Ch6_Quantitative_Nanomechanics_Python_Exercises.ipynb)

---

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
    │   ├── ch04_afm_imaging_modes
    │   │   ├── README.md
    │   │   └── SPM_Ch4_AFM_Imaging_Modes_Python_Exercises.ipynb
    │   ├── ch05_force_distance_curve_analysis
    │   │   └── SPM_Ch5_Force_Distance_Curve_Python_Exercises.ipynb
    │   └── ch06_quantitative_nanomechanics
    │       └── SPM_Ch6_Quantitative_Nanomechanics_Python_Exercises.ipynb
    └── utils
        └── README.md

11 directories, 17 files
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
