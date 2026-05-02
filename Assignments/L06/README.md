# L06 – IIoT Time Series Forecasting Lab

## Objective
The goal of this lab was to apply time-series forecasting techniques to IoT temperature data, including preprocessing, modeling, evaluation, and data augmentation using deep learning.

## What I Did
- Loaded and analyzed a real-world IoT dataset (97K+ records)
- Converted timestamps and structured data for time-series analysis
- Created lag features and rolling mean features
- Split data into training and testing sets (80/20)
- Implemented SeasonalNaive forecasting model using StatsForecast
- Evaluated model performance using MAE, MSE, and RMSE
- Applied rolling-origin cross-validation
- Built a Variational Autoencoder (VAE) for synthetic data generation
- Augmented dataset and retrained model

## Results
Original Model:
- MAE: 4.65
- RMSE: 5.73

Augmented Model:
- MAE: 5.22
- RMSE: 6.18

## Key Insight
Synthetic data generated using VAE did not improve performance, highlighting the importance of data quality in machine learning workflows.

## Technologies Used
- Python
- Pandas
- StatsForecast (Nixtla)
- Scikit-learn
- TensorFlow / Keras
- Time-Series Analysis

## Files Included
- Jupyter Notebook (.ipynb)
- Colab Export (.pdf)
- Written Report (.docx)
