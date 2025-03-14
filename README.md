# Towards Learning Convolutions from Scratch

This repository contains the implementation and analysis of our **Reproducibility Challenge** project for **EE-411 (2023-2024)**. We investigate the claims from the paper **"Towards Learning Convolutions from Scratch"** by Behnam Neyshabur, focusing on training **fully connected networks** with **β-lasso regularization** to learn convolutional-like filters.

## 📌 Project Overview

- **Goal**: Evaluate the effectiveness of learning convolutions from scratch by replacing convolutional layers with fully connected ones trained using **β-lasso optimization**.
- **Approach**:
  - Reproduced and analyzed key results from the paper, particularly **Table 2, Fig. 3, and Fig. 4**.
  - Implemented **shallow neural networks** to compare different architectures:
    - **Sconv (Shallow Convolutional Network)**
    - **Slocal (Shallow Local Network)**
    - **SFC (Shallow Fully Connected Network)**
    - **3FC (3-Layer Fully Connected Network)**
  - Evaluated performance on **CIFAR-10, CIFAR-100, and SVHN** datasets.
  - Studied the impact of **β-lasso** in enforcing sparsity.

## 📂 Repository Structure

- **📄 `FOIL_Project_Alnuaimee_Cammarata_Sahebi.pdf`**
  - Final report detailing our implementation, results, and analysis.

- **📄 `paper.pdf`**
  - An updated version of the research paper containing our findings.

- **📜 `Graph_generator1_Alnuaimee_Cammarata_Sahebi.ipynb` & `Graph_generator2_Alnuaimee_Cammarata_Sahebi.ipynb`**
  - Scripts for generating figures 1 and 2 of the report

- **📜 `Paper3_Alnuaimee_Cammarata_Sahebi.ipynb`**  
  - Implements **four neural network architectures**:  
    - **S_CONV** (Shallow CNN)  
    - **S_LOCAL** (Locally connected network using grouped convolutions)  
    - **S_FC** (Fully connected network)  
    - **FC_3** (Three-layer fully connected network)  
  - Defines **training hyperparameters** (batch size, learning rate, etc.).
  - Loads and processes the **CIFAR-10 dataset**.
  - Provides a baseline evaluation of network performance.

- **📄 `Projects_EE411__23_24.pdf`**
  - list of projects proposed by EE-411 project.

- **📜 `.gitattributes`**
  - Git configuration file.

- **📄 `README.md`**
  - You are here! Documentation about the project.

