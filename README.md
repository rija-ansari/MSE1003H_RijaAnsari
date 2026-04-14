# MSE1003H_RijaAnsari— Data & Analytics for Materials Engineering / Advanced AI for Accelerated Materials Discovery

**University of Toronto** 

This repository contains all assignments and the final project for MSE1003H. The course covers the full machine learning and active learning pipeline as applied to materials science, from data featurization and modeling through self-driving laboratory experiments.

---

## Assignments

### Assignment 1 — Data Featurization and Modeling

Implements a full ML pipeline on the Materials Project Database to predict or classify material bandgap.

---

### Assignment 2 — Design of Experiments (Opentron-2)
**Platform:** Opentron-2 color-mixing robot (RYB dyes)

Designs and executes a structured design of experiments (DOE) using the Opentron-2 robotic platform, collecting 8-channel spectral response data for use in Assignments 3 and 4.
---

### Assignment 3 — Single-Objective Optimization
Uses active learning to converge on a target 8-channel spectral response from the Opentron-2. 
---

### Assignment 4 — Multi-Objective Optimization & Inference

Implements Bayesian optimization for three simultaneous objectives on a self-driving corrosion study platform using acid/base volume ratios as inputs.

- **Objectives 1 & 2:** Determine parameters *a* and *b* in the Henderson-Hasselbalch equation
- **Objective 3:** Predict pitting corrosion potential *E*_pitt for a target acid/base ratio

---

### Final Project — Community Science and Self-Driving Labs

Develops an acquisition policy for a 3D-printed energy-absorbing structure optimization experiment, with five iterative rounds of experiment selection from a shared pool.

**MSE1003 goal:** Maximize both scientific discovery and community engagement, incorporating proposed experiments from community scientists.

### Data access

- Materials Project data: downloaded via the `mp_api` client (see Assignment 1 notebook for setup)
- Opentron-2 data: collected during allocated lab time slots; CSVs stored in the respective assignment folders
- Final project dataset: downloaded from Quercus

> **Note:** All notebooks use  `random_seed = 1003` (MSE1003) for reproducibility. Do not change this value.
