# liver-tumor-segmentation-info


**Note:** This repository only contains the project description. The full project code is stored in a private repository.

---

# Liver Tumor Segmentation Project

This project involves developing an advanced liver tumor segmentation model using a UNet architecture with a ResNet50 encoder. By leveraging DICOM data preprocessing, CLAHE-based image enhancement, and radiomics feature extraction with PyRadiomics, the model achieves high segmentation accuracy.

## Overview
The goal of this project is to accurately segment liver tumors from DICOM images using a custom deep learning model. The segmentation model was trained on the "Liver Tumor Segmentation - Part 1 and Part 2" datasets from Kaggle, achieving approximately 95% accuracy.

## Features
- **Preprocessing**: Utilizes CLAHE (Contrast Limited Adaptive Histogram Equalization) and edge detection techniques to enhance DICOM image quality before segmentation.
- **Segmentation Model**: Employs a custom UNet model with ResNet50 as the encoder for precise liver tumor segmentation.
- **Radiomics Feature Extraction**: Extracts comprehensive radiomics features from the segmented tumor masks using PyRadiomics, providing detailed insights for further analysis.

## Dataset
The dataset used is the "Liver Tumor Segmentation - Part 1 and Part 2" from Kaggle, which includes DICOM images of liver scans with corresponding tumor masks.

## Requirements
- **Python 3.8+**
- **PyTorch**: Deep learning framework
- **OpenCV**: For image processing
- **NumPy**: Numerical computations
- **PyRadiomics**: Radiomics feature extraction
- **GDCM & Pylibjpeg**: Essential for handling DICOM images

## How to Use

1. **Prepare the dataset**: Download the dataset from Kaggle and place it in the designated folder.
2. **Train the model**: Execute the training script to train the segmentation model.
3. **Evaluate the model**: Use the evaluation script to test the model on new DICOM images.

---
