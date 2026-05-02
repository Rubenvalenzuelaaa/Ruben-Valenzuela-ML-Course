# A06 – IIoT Time Series Forecasting Project

## Objective
The goal of this group project was to explore time-series forecasting techniques for Industrial IoT temperature data using statistical models and deep learning approaches.

## What We Did
- Analyzed a real-world IoT temperature dataset (97K+ records)
- Prepared time-series data (timestamp processing, feature engineering, cleaning)
- Implemented a SeasonalNaive model for forecasting
- Applied rolling-origin cross-validation
- Explored Variational Autoencoders (VAE) for data augmentation

## Key Results
- Baseline model achieved strong performance:
  - MAE: 4.65
  - RMSE: 5.73
- VAE augmentation reduced performance:
  - MAE increased by ~12%
  - RMSE increased by ~8%

## Key Insights
- Simple statistical models perform well with strong seasonal patterns
- Synthetic data must be high quality to improve results
- Poor augmentation can negatively impact model accuracy

## Technologies Used
- Python
- StatsForecast
- Time-series analysis
- Variational Autoencoders (VAE)

## Files Included
- Presentation (.pptx)
