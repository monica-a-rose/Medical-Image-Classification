# Deep Learning for Medical Image Classification

### 📖 [View the Full Project Report (PDF)](Medical_Image_Classification.pdf)

---

## Project Overview

This project demonstrates an end-to-end pipeline for classifying histopathology images using a Convolutional Neural Network (CNN). The primary goal was to develop a deep learning model that could accurately classify five types of tissue from the **PathMNIST** dataset and systematically prove its superiority over traditional machine learning methods.

This repository serves as a portfolio piece to showcase the skills and methodologies applied. For a comprehensive walkthrough of the code, analysis, and findings, please see the link to the full report above.

## Dataset

This project uses the **PathMNIST** dataset, which is part of the MedMNIST v2 collection, a large-scale benchmark for biomedical image classification. The dataset is based on the PatchCamelyon (PCam) dataset and consists of 100,000 non-overlapping image patches from histopathologic scans of lymph node sections.

*   **Source:** The dataset can be downloaded from the official MedMNIST repository on Zenodo or from the [MedMNIST GitHub](https://github.com/MedMNIST/MedMNIST/).
*   **Citation:** Kather, J. N., Krisam, J., & Charoentong, P. (2019). Predicting survival from colorectal cancer histology slides using deep learning: A retrospective multicenter study. *PLOS Medicine*, 16(1), e1002730.

## Key Features & Methodology

*   **Model Development:** A 3-layer CNN was built and trained using **PyTorch** to perform multi-class image classification.
*   **Baseline Benchmarking:** The CNN's performance was rigorously compared against **scikit-learn** baselines (Logistic Regression and Random Forest) to validate the effectiveness of the deep learning approach.
*   **End-to-End Pipeline:** Implemented a full data pipeline featuring image preprocessing, data augmentation (random flips and rotations), and a hyperparameter grid search to optimize model performance.
*   **Performance Evaluation:** Final model performance was evaluated on a hold-out test set using metrics such as accuracy, precision, recall, and F1-score, supported by confusion matrices.

## Final Performance

The final optimized CNN achieved a **test accuracy of 90.9%**, demonstrating a **22.1 percentage point performance uplift** over the strongest baseline model (Random Forest).

## Technologies Used

*   **Python**
*   **PyTorch:** For building and training the CNN.
*   **Scikit-learn:** For baseline models and performance metrics.
*   **NumPy:** For numerical data manipulation.
*   **Matplotlib & Seaborn:** For data visualization and plotting results.
