# Modal Analysis of a Cantilever Beam

> **Academic Laboratory Activity — Politecnico di Milano**  
> Course: *Advanced Dynamics of Mechanical Systems* (A.Y. 2024–2025)  
> **Authors:** Simone Falsitta, Francesca Gaudiano, Gabriele Massa, Alessandro Morini
> **Advisors:** Prof. Roberto Corradi, Prof. Ivano La Paglia

---

## Project Overview
This repository contains the complete analytical, numerical, and experimental modal analysis of a rectangular aluminum cantilever beam. The study investigates free and forced vibrations, complex frequency response functions (FRFs), and parameter identification techniques using MATLAB.

## Key Technical Sections

1. **Reference Structure & Data:**
   * Geometry: Length $L = 1200\text{ mm}$, Thickness $h = 8\text{ mm}$, Width $b = 40\text{ mm}$.
   * Material: Aluminum (Density $\rho = 2700\text{ kg/m}^3$, Young's Modulus $E = 68\text{ GPa}$).

2. **Vibration Modes & Natural Frequencies:**
   * Analytical standing wave solution based on Euler-Bernoulli beam theory.
   * Enforcement of clamped-free boundary conditions to build the coefficient matrix $H(\omega)$.
   * Numerical root-finding of the characteristic equation ($\det[H(\omega)] = 0$) to extract the first four natural frequencies ($4.50\text{ Hz}, 28.23\text{ Hz}, 79.03\text{ Hz}, 154.87\text{ Hz}$).

3. **Frequency Response Functions (FRFs):**
   * Modal superposition approach to compute receptance and inertance.
   * Analysis of **co-located FRFs**, **controllability** (nodal excitation limits), **observability** (sensor placement effects), and verification of the **reciprocity principle**.

4. **Experimental Identification:**
   * Least-squares curve fitting optimization via MATLAB's `lsqnonlin` function.
   * Processing data from simulated dual-accelerometer configurations to estimate damping ratios, natural frequencies, and modal residues.

---
## Project Team & Academic Context

## Group Members
* **Simone Falsitta**
* **Francesca Gaudiano** 
* **Gabriele Massa** 
* **Alessandro Morini**

**Politecnico di Milano 1863**  
*School of Industrial and Information Engineering — M.Sc. in Mechanical Engineering* (A.Y. 2024–2025)  
**Course**: *Advanced Dynamics of Mechanical Systems*
**Supervisors**: Prof. Roberto Corradi, Prof. Ivano La Paglia
