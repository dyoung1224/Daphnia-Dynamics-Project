# Daphnia Dynamics Project

A unified research codebase for analyzing collective and individual motion dynamics in *Daphnia magna*, with an emphasis on extracting quantitative behavioral and kinematic features from tracking data.

This project consolidates multiple analysis pipelines used in biophysics and collective-behavior research, including displacement statistics, rotational dynamics, and handedness (left/right turning bias).

-----

## Project Overview

Understanding how simple organisms move—both individually and collectively—provides insight into emergent behavior, biological decision-making, and physical constraints on motion.

This repository serves as an **umbrella project** that organizes several focused analysis modules, each addressing a different aspect of *Daphnia* locomotion. The modules are maintained as independent repositories and linked here as submodules to preserve modularity and reproducibility.

-----

## Analysis Modules

- **Displacement Analysis**  
  Quantifies displacement distributions and trajectory-based kinematic metrics, including step-length statistics and related measures.

- **Rotational Dynamics Analysis**  
  Analyzes angular motion, rotational persistence, and orientation-based dynamics of individual trajectories.

- **Handedness Analysis**  
  Examines left/right turning bias and turning-angle asymmetries at the individual and population levels.

- **TREX NPZ → CSV Tools**  
  Utilities for converting TREX tracking outputs (`.npz`) into analysis-ready tabular formats.

Each module can be used independently or as part of the full analysis pipeline.

-----

## Pipeline Summary

1. Video tracking is performed using **TREX**.
2. TREX outputs trajectory data in `.npz` format.
3. Conversion and preprocessing tools generate clean, analysis-ready datasets.
4. Specialized analysis modules extract dynamical and statistical features.
5. Results are visualized and summarized for interpretation and reporting.

-----

## Repository Structure

This repository links the following submodules:

- `displacement/` — displacement and kinematic analysis  
- `rotational_dynamics/` — angular and rotational behavior  
- `handedness/` — turning bias and asymmetry  
- `trex_tools/` — data conversion and preprocessing utilities  

Refer to each module’s README for implementation details and usage instructions.

-----

## Status

Active development.  
The codebase is used for ongoing research and may evolve as analyses are extended or refined.

---

## Author(s)

- David Young (University of Pennsylvania - Computer & Informatics Department)
- Oleg Kogan (CUNY Queens College - Physics Department)
- Sebastian Alvarado (CUNY Queens College - Biology Department)
