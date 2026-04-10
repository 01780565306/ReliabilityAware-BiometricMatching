[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/REPO_NAME/blob/main/reliability_biometric_demo.ipynb)

# Reliability-Aware Biometric Matching with Calibrated Uncertainty

**Author:** Kayes Bin Yousuf | Incoming MS ECE, Clarkson University

**Based on:** Venkataswamy et al. (2026) - Temporal Degradation
in Iris Biometric Matching
## Overview
A proposed reliability-aware extension to the Venkataswamy et al.
biometric matching framework, adding calibrated probability
estimation and formal coverage guarantees via conformal prediction.

## Key Contributions
- Baseline: Fixed threshold (VeriEye manufacturer threshold = 36)
- Linear Mixed-Effects Model mirroring the paper's statistical approach
- Isotonic Regression calibration: raw scores → P(genuine)
- Quality-adaptive threshold based on the paper's false non-match findings
- Split Conformal Prediction with distribution-free coverage guarantee
- Strict train/val/test split - no data leakage
- Unit tests (Cell 13) for all core functions
## How to Run
Click the **Open in Colab** badge above to run instantly.
No external dataset required - genuine/impostor comparison scores
are simulated consistent with Venkataswamy et al. (2026).

