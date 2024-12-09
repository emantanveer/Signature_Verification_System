# Signature_Verification_System

This project implements a system for verifying signatures as either **genuine** or **forged** using **Histogram of Oriented Gradients (HOG)** for feature extraction and a **Support Vector Machine (SVM)** for classification. It processes signature images, extracts meaningful features, and performs classification with high accuracy.

## Overview
- **Goal:** To automate the verification of handwritten signatures.
- **Key Components:**
  - Feature extraction using HOG.
  - Classification using SVM.
  - Image preprocessing for robust feature extraction.

## Features
- **Genuine vs Forged Classification:** Detects whether a signature is genuine or forged.
- **HOG Feature Extraction:** Employs optimized parameters for extracting signature features.
- **Performance Evaluation:** Displays accuracy and confusion matrix for analysis.

## Results
- The model achieved a maximum accuracy of **83.33%** on the provided dataset.
- Accuracy can be improved further by increasing the number of training samples.
