# sleep-apnea-ecg-dl
# Sleep Apnea Prediction using Machine Learning and Deep Learning

This project investigates classical machine learning and deep learning models for Obstructive Sleep Apnea (OSA) prediction.

## Machine Learning Experiments

Two supervised tasks were studied:

- Regression: Prediction of Apnea-Hypopnea Index (AHI)
- Classification: Healthy vs Severe OSA classification

Classical models:
- Linear Regression, SVR, Random Forest (Regression)
- Logistic Regression, SVM, Random Forest (Classification)

Evaluation:
- Regression metrics: MAE, RMSE, R2
- Classification metrics: Accuracy, F1-score, AUC
- Feature ablation study using BMI and Cervical Circumference

## Deep Learning Experiments

Deep learning models were trained on raw ECG signals from the PhysioNet Apnea-ECG dataset:

- CNN
- LSTM
- CNN-LSTM hybrid model

Evaluation was performed using subject-level train/validation/test split with AUC and F1-score.

## Dataset

Machine learning experiments used anthropometric data.  
Deep learning experiments used the PhysioNet Apnea-ECG dataset.

The datasets are not included due to licensing restrictions.

## Author

Savvas Kakalis  
Universidad Politécnica de Madrid
