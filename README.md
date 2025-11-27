# Medical Imaging Radiomics Analysis Project

This project provides a complete pipeline for medical imaging radiomics feature extraction and machine learning analysis, specifically designed for processing Ultrasound Shear Wave Elastography (SWE) and other medical imaging data.

## Project Files

### Step1.1 Rad-SWE OR 2D.ipynb
**Data Preprocessing Module**
- Medical imaging data format validation
- Image and mask alignment verification
- Multi-modal data support configuration
- Label data reading and integration

### Step1.2 Rad-SWE OR 2D.ipynb  
**Radiomics Feature Extraction and Analysis Module**
- PyRadiomics feature extraction (1562 radiomics features)
- Feature statistics and visualization
- Data standardization processing
- Feature correlation analysis
- Lasso feature selection
- Machine learning model training (LR, SVM, RF, etc.)
- Model evaluation and visualization (AUC, ROC, confusion matrix)

## Main Features

### Data Management
- Support for multi-modal medical imaging data (CT, MRI, SWE, etc.)
- Automatic verification of images and masks file correspondence
- Label data integration and group management

### Feature Engineering
- Traditional radiomics feature extraction based on PyRadiomics
- Support for first-order statistical features, texture features, shape features, etc.
- Feature standardization and outlier detection
- Feature screening based on correlation coefficients and Lasso

### Machine Learning Modeling
- Automatic dataset splitting (training set/test set)
- Support for multiple classification algorithms
- Cross-validation and hyperparameter optimization
- Comprehensive model performance evaluation

## Environment Requirements

```bash
Python 3.7+
Jupyter Notebook
onekey_algo (dedicated algorithm library)
PyRadiomics
scikit-learn
pandas
numpy
matplotlib
