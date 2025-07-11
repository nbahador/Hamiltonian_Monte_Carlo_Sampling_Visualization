# Hamiltonian Monte Carlo Sampling Visualization
This is an **educational tool** for understanding HMC, a key algorithm in Bayesian statistics and machine learning!

![HMC Visualization Preview](https://github.com/nbahador/Hamiltonian_Monte_Carlo_Sampling_Visualization/blob/main/img.png)

---

## 🔗 Interactive Demo

[**View Live Demo**](https://nbahador.github.io/Hamiltonian_Monte_Carlo_Sampling_Visualization/Hamiltonian%20Monte%20Carlo%20Sampling.html)

---

## Overview

This is an interactive visualization of **Hamiltonian Monte Carlo (HMC)**, a Markov Chain Monte Carlo (MCMC) sampling algorithm used in statistics and machine learning.

---

## What You'll See

| Component | Description |
|-----------|-------------|
| **3D Probability Landscape** | Dark, gradient-colored 3D surface representing probability distribution (higher points = lower probability, valleys = high probability) with a **red ball** showing current sampler position |
| **2D Projections** | Left panel shows contour lines of probability distribution; Right panel displays gradient vector field |
| **Minimap** | Bottom-right display showing exploration history (green = accepted moves, red = rejected moves) |
| **Controls Panel** | Start/Pause/Reset buttons, parameter sliders, and real-time statistics |
| **Dynamic Arrows** | Gold arrow shows momentum direction; Pink arrow shows gradient direction |

---

## Key Features

### HMC Simulation Phases
- **Momentum Sampling (Gold)**: Random momentum assigned to the ball
- **Exploration (Blue)**: Ball follows Hamiltonian dynamics
- **Decision (Orange)**: Move evaluated for acceptance
- **Accepted (Green)**: Move kept (high probability region)
- **Rejected (Red)**: Move discarded (low probability region)

### Interactive Controls
| Parameter | Effect |
|-----------|--------|
| **Step Size** | Controls accuracy of Hamiltonian dynamics simulation |
| **Leapfrog Steps** | Affects exploration precision |
| **Mass** | Influences momentum impact on movement |
| **Temperature** | Controls momentum sampling randomness |

### Energy Visualization
- **Potential Energy (U)**: Negative log-probability
- **Hamiltonian (H)**: Total energy (potential + kinetic)

---

## Why This Matters

HMC is **more efficient** than traditional MCMC methods because it uses gradient information to avoid random walks. This visualization helps **intuitively understand** how HMC explores complex probability distributions.

---

## How to Interact

1. Click **"Start HMC"** to begin sampling
2. Adjust sliders to see parameter effects on performance
3. Watch ball movement - **accepted moves** go to high-probability regions
4. Observe **gradient arrows** guiding motion
5. Monitor **acceptance rates** and **exploration efficiency**

---

![Conceptual Demo](https://github.com/nbahador/Hamiltonian_Monte_Carlo_Sampling_Visualization/blob/main/img2.png)

[**View Conceptual Demo: HMC for Adaptive Agentic Systems**](https://nbahador.github.io/Hamiltonian_Monte_Carlo_Sampling_Visualization/Conceptual%20Demo%20HMC%20for%20Adaptive%20Agentic%20Systems.html)

Hamiltonian Monte Carlo (HMC) sampling can be integrated with agentic workflows to create self-improving service systems. HMC samples from posterior distributions of transition probabilities using citizen satisfaction data, enabling continuous optimization while preserving ergodic properties and convergence guarantees.
