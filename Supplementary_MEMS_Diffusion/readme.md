# Supplementary Information: Fingerprint-Conditioned Diffusion for Zero-Shot Cross-Chip MEMS IMU Calibration

This repository provides the supplementary information for the paper:

> **Fingerprint-Conditioned Diffusion for Zero-Shot Cross-Chip MEMS IMU Calibration**

The repository accompanies the manuscript submitted to ICASSP and contains the materials referenced in the paper's supplementary PDF. It is intended to support reproducibility and to provide the extended results that could not be included in the main paper due to the page limit.

## Contents

- **Wuhan Split 2 and Split 3 results** — per-chip, per-axis drift values for the additional evaluation splits discussed in the main paper.
- **Ablation studies** — results for the `No-FP`, `No-Drift`, and `No-Contrast` variants across all three splits.
- **Held-out chip statistics** — per-chip error standard deviations used to define the in-distribution, mild out-of-distribution, and extreme out-of-distribution cases.
- **Fingerprint diagnostic** — cosine similarity analysis of the learned fingerprint vectors across two controlled pairing conditions.
- **Aggregate relative-reduction summary** — mean and median reductions versus the raw and linear-calibration baselines, with bootstrap confidence intervals.

## Data and Models

The experiments are based on publicly available datasets:

- **Wuhan IMU array** — 16 nominally identical MEMS IMU chips recorded alongside a tactical-grade Leador-A15 reference.
- **ALiMU** — three low-grade IMU models (BMX160, MPU9250, LSM9DS1) recorded alongside an industrial-grade VN100 reference.
- **NavINST** — an Xsens MTi-670G industrial IMU and a Livox MEMS IMU recorded on a shared rigid body.

If you use these datasets, please cite the corresponding dataset papers as listed in the main manuscript.

## Citation

If you find this work useful, please cite it.
