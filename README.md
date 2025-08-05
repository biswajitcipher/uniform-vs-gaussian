# Comparing Discrete Gaussian and Uniform Distributions

This repository contains two Python notebooks that analyze and visualize the **statistical closeness** between discrete Gaussian and uniform distributions. 
These experiments are particularly relevant for cryptographic applications such as **Learning With Errors (LWE)** and its variants, 
where different noise distributions impact security and performance.

---

##  Files

- `gaussian and uniform distribution closeness check.ipynb`  
  Compares the discrete Gaussian distribution and uniform distribution over a finite range using statistical metrics and plots.

- `uniform vs discrete gaussian.ipynb`  
  Investigates how close a discrete Gaussian is to a uniform distribution over a modular ring (e.g., \( \mathbb{Z}_q \)) using empirical divergence metrics and entropy estimates.

---

##  Objectives

- Visualize and quantify how close a discrete Gaussian distribution is to uniform.
- Estimate statistical distances (e.g., \( L_1 \) distance, total variation).
- Measure entropy and Rényi divergence (Future Plan).
- Provide evidence for theoretical claims regarding indistinguishability between distributions in cryptographic contexts.

---

##  Techniques Used

- Histogram comparison of sampled distributions.
- Total variation distance calculation.
- Empirical min-entropy and Shannon entropy estimation. ---> Future Plan
- Optional: Rényi divergence or KL-divergence between distributions. ----> Future plan

---

## ⚙ Requirements

Install the required Python libraries:

```bash
pip install numpy scipy matplotlib seaborn
