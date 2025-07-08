# FraudCluster_KMeans
![Status](https://img.shields.io/badge/RepoStatus-Public-green)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![License](https://img.shields.io/github/license/MrRincon/FraudCluster_KMeans)

![Owner](https://img.shields.io/badge/Alam-Rincon-orange)
![Owner](https://img.shields.io/badge/Petar-Atanasov-orange)
![Owner](https://img.shields.io/badge/Teon-Morgan-orange)

This project focuses on developing a model to detect financial fraud in unlabelled transaction data to showcase skills related to machine learning workflows and ethics. The goal is to separate the unusual and suspicious transactions from the group of common or normal transaction, contributing towards secured transactional procedures and fraud analysis.

---
## Dataset Reference
Khorasani, V. (2024) 'Bank Transaction Dataset for Fraud Detection'. Available at: https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection (Accessed: 24 June 2025). Available license at: https://www.apache.org/licenses/LICENSE-2.0.

---
## Problem Solved
The clustering model addresses the challenge of detecting financial fraud in unlabelled transaction data using unsupervised learning. By Applying PCA for dimensionality reduction and K-Means clustering to group behavioural patterns. The model identifies outliers (transactions far from the cluster centroids), as potential fraud. Feature scaling, TTB ratios, and cluster evaluation metrics like the elbow method and silhouette scores enhance accuracy and efficiency in spotting anomalies.

---
## Motivation
The motivation behind this project is to address the challenge of financial fraud due to the large volumes of unlabelled transaction data, where traditional detection methods fall short.

---
## Requirements
  ### Jupyter Setup
    - Install Anaconda (Python 3.11+ recommended).
    - Launch JupyterLab via Anaconda Navigator.
    - Use a Python 3 kernel in JupyterLab.
  ### Colab Setup
    - Add the project in a folder, include also the dataset into it.
    - Mount the drive on the notebook at the beginning.
  ### Project Setup Instructions
    - Clone the repository and create a folder called 'datasets' in the root directory.
    - Download the dataset from Kaggle and place the .csv file in the dataset folder.

## Table of Contents
1. Project Overview
2. Dataset Reference
3. Problem Solved
4. Motivation
5. Requirements
  - Jupyter Setup
  - Colab Setup
  - Project Setup Instructions
6. Notebook Structure
  - Dataset Selection and Problem Definition
  - Data Preprocessing 
    - Feature Selection and Augmentation
  - Exploratory Data Analysis
  - Model Development and Evaluation 
    - K-Means for Fraud Detection
    - Outlier Identification
    - Analyse Clusters
  - Ethical Considerations

