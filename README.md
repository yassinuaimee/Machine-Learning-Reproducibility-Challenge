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

- **📜 `Graph_generator1_Alnuaimee_Cammarata.py` & `Graph_generator2_Alnuaimee_Cammarata.py`**
  - Scripts for generating performance and weight distribution visualizations.

- **📄 `Paper3_Alnuaimee_Cammarata_Sahebi.pdf`**
  - A related paper discussing alternative perspectives.

- **📄 `Projects_EE411__23_24.pdf`**
  - Course document related to the EE-411 project.

- **📜 `.gitattributes`**
  - Git configuration file.

- **📄 `README.md`**
  - You are here! Documentation about the project.

## 🚀 How to Use the Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/yassinuaimee/Towards-Learning-Convolutions.git
   cd Towards-Learning-Convolutions
