# Machine Learning based Characterization of Photonic Crystals

## Overview
This project investigates the potential of **machine learning (ML)** as a complementary tool in **photonics** for the characterization of **photonic crystals (PhCs)**.

Using **COMSOL Multiphysics**, electromagnetic wave propagation through photonic crystals with varying configurations is simulated and the resulting **band structures** are generated and visualized. Building on this simulation data, a **supervised learning approach** is applied, employing a **convolutional neural network (CNN)** for image recognition to predict photonic band structures from previously unseen input data.

---

## Project Scope and Structure

### 1. Theoretical Background
The first part of the study focuses on the theoretical foundations of photonic crystals, examining the connection between **solid-state physics** and **electromagnetism**, and explaining the physical origin of photonic band structures.

This section also introduces the principles of **machine learning** and **convolutional neural networks**, with particular emphasis on the numerical operations underlying deep learning models that are relevant to this work.

### 2. Methodology
The methodology is divided into two main components:

- **Photonic Crystal Simulations**  
  Numerical simulations of photonic crystals are performed using **COMSOL Multiphysics** to obtain band structures for different geometrical and material configurations.

- **CNN Architecture and Training**  
  A step-by-step explanation of the convolutional neural network architecture is provided, detailing data preprocessing, model design, training procedure, and evaluation strategy used to predict band structures from simulation outputs.

### 3. Results and Analysis
The results section presents:
- Simulated band structures
- CNN predictions on unseen data
- Graphical comparisons and accuracy metrics

These results are used to assess the effectiveness and limitations of the ML-based approach.

### 4. Conclusion and Future Work
The study concludes with a summary of key findings and discusses potential extensions, including improvements to model accuracy, dataset expansion, and future applications of machine learning in photonic crystal research.

---

## Technologies Used
- **COMSOL Multiphysics**
- **Python**
- NumPy, SciPy, Matplotlib
- Machine Learning / Deep Learning (CNN)

## Academic Context
This repository contains a university project completed as part of an academic course.  
