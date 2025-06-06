# Fraud Detection Model

## Overview

This project implements a deep learning-based fraud detection system using TensorFlow and Keras. It addresses the challenge of detecting rare fraudulent transactions in highly imbalanced datasets.

---

## Features

- Neural network model trained on imbalanced transaction data  
- Handles extreme class imbalance with high recall and acceptable precision  
- Model evaluation using precision, recall, F1-score, and ROC-AUC  
- Model versioning and serialization using TensorFlow SavedModel format  
- Containerized inference service with Docker  
- REST API for real-time fraud prediction using FastAPI  
- Automated CI/CD pipeline for seamless testing and deployment  
- Monitoring of model performance and data drift with Prometheus and Grafana  
- Automated ETL pipelines for preprocessing and feature engineering  

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sayed-ashfaq/CreditCard_FraudDetection_NN
   cd CreditCard_FraudDetection_NN
   
