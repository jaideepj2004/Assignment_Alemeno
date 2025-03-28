# assignment_summer_internship

This repository contains the code and documentation for the QR Code Authentication assignment. The objective is to classify QR code images as either "first print" (original) or "second print" (counterfeit) using both traditional machine learning and deep learning approaches.

## Contents
- **Documentation PDF:** A complete report (4-6 pages) detailing the project approach, methodology, experiments, evaluation, and deployment considerations.
- **Code:** All code used for feature extraction, model development, evaluation, and deployment considerations.
- **GitHub Repository:** This repository hosts the complete project code, organized into logical sections.

## Project Overview
- **Dataset:** Consists of 200 QR code images:
  - 100 images of original QR codes (first prints with embedded Copy Detection Patterns)
  - 100 images of counterfeit QR codes (second prints, created by scanning and reprinting the originals)
- **Feature Engineering:** Extracted features include brightness, GLCM properties, LBP, and wavelet-based features.
- **Models:** 
  - Traditional Machine Learning Models: SVM, Logistic Regression, Naïve Bayes, Decision Tree, KNN, Random Forest, XGBoost, AdaBoost, Gradient Boosting.
  - Deep Learning Models: Custom CNN and InceptionV3-based model (using transfer learning).
- **Evaluation:** Models were evaluated based on accuracy, precision, recall, F1-score, and confusion matrices.
- **Deployment Considerations:** Includes analysis of inference time, memory usage, robustness to scanning conditions, and security implications.

## Getting Started

### Prerequisites
- Python 3.x
- Packages: OpenCV, NumPy, Matplotlib, scikit-learn, scikit-image, xgboost, TensorFlow, etc.
- Jupyter Notebook (optional, for running and modifying the notebook)

### Installation
Clone the repository:
```bash
git clone https://github.com/jaideepj2004/Assignment_Alemeno.git
