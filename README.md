# Blockchain-Based-Fraud-Detection-System

Overview

This project implements a fraud detection system leveraging blockchain technology and machine learning. It combines the transparency and security of blockchain with advanced fraud detection models to identify anomalies and prevent fraudulent transactions.


Features

Machine Learning Integration: Utilizes Random Forest, XGBoost, and other models for accurate fraud detection.
Data Processing: Employs robust preprocessing techniques, including over-sampling (SMOTE) for class imbalance.
Visualization: Provides insights through detailed plots and interactive dashboards.
Blockchain Backend: Ensures transparency and immutability for fraud data storage.
Scalability: Can be extended for real-world deployment with blockchain frameworks.

Usage

Preprocessing:
Load the dataset and apply necessary transformations.
Balance the dataset using SMOTE.
Model Training:
Train machine learning models such as Random Forest and XGBoost.
Fine-tune models using GridSearchCV.
Evaluation:
Visualize confusion matrices, ROC curves, and classification reports.
Integration:
Export trained models using pickle for deployment.
Integrate with a blockchain for data storage and logging.

Visualizations

The project includes:

Confusion Matrix for model evaluation.
ROC curves for assessing model performance.
Interactive dashboards using Plotly.
Future Enhancements

Full blockchain integration for storing fraud logs securely.
Deployment of the model as an API.
Real-time monitoring system for fraud detection.
