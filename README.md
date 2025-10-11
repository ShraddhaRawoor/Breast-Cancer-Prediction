# Breast Cancer Prediction

A machine learning project that predicts whether a breast tumor is **malignant** or **benign** using Python and common ML libraries.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Author](#author)

---

## Overview
This project uses machine learning algorithms to classify breast cancer tumors based on features such as radius, texture, perimeter, area, smoothness, and more. The model helps in early detection, which can be crucial for treatment and survival rates.

---

## Dataset
The project uses the **Breast Cancer Wisconsin Dataset** available from [scikit-learn](https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset).  
It contains 569 samples of tumors with 30 features and a target variable (`malignant` or `benign`).

---

## Features
Some important features used in this dataset include:  
- Radius (mean of distances from center to points on the perimeter)  
- Texture (standard deviation of gray-scale values)  
- Perimeter  
- Area  
- Smoothness  
- Compactness  
- Concavity  
- Symmetry  

---

## Technologies
- Python 3.x  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## Installation
1. Clone the repository:

```bash
git clone https://github.com/ShraddhaRawoor/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction
```
2.Install dependencies:
```bash
pip install -r requirements.txt
```
If requirements.txt is not available, install packages manually:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```
---
##Usage
1.Open the Jupyter Notebook:
```bash
jupyter notebook
2.Run the notebook Breast_Cancer_Prediction.ipynb step by step.
3.Explore data preprocessing, model training, evaluation, and visualization.
```
#Results
The trained model predicts tumor malignancy with high accuracy. You can view the model performance metrics (accuracy, confusion matrix) in the notebook.
Author
