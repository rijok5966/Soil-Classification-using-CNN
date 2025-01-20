# Soil-Classification-using-CNN

## Overview
  This project explores the classification of six distinct soil types using Convolutional Neural Networks (CNNs). By leveraging deep learning techniques, the study aims to enhance the accuracy and efficiency of soil classification, addressing challenges faced by traditional methods. The outcomes contribute to environmental sustainability, agricultural decision-making, and soil management practices.

## Data Description
  - Dataset Composition: The dataset cosists of types of Soil (Alluvial, Clayey, Laterite, Loamy, Sandy Loam, and Sandy Soil) with varying sample sizes.

## Key Highlights
  - Data Augmentation: The images were standardized to 256x256 pixels in RGB format and later augmented using techniques such as rotation, zoom, shear, and flipping improved model generalization.
  - Model Performance: Base CNN achieved 64.10% accuracy with a test loss of 0.9087. Enhanced performance using Dropout and Early Stopping techniques reached an accuracy of 84.62%.
  - Regularization Techniques:
      - Dropout: Reduced overfitting by randomly deactivating neurons during training.
      - Early Stopping: Prevented overfitting by halting training when validation performance ceased to improve.

## Repository Contents
  - Report: Detailed analysis and methodology are documented in the PDF file.
  - Code: The ipynb file consists of the Python scripts used for data preprocessing, CNN implementation, and model evaluation.

## Acknowledgments
  - Dataset Source: Kaggle.
  - References: Inspired by research on CNNs and soil classification.
