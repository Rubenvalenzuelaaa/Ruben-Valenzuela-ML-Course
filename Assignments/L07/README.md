# L07 – IIoT Network Analysis: Age of Information and Reliability Trade-offs

## Objective
The goal of this lab was to analyze network performance in IIoT systems by studying the trade-off between data freshness (Age of Information) and reliability (packet loss probability).

## What I Did
- Explored and cleaned a real IIoT dataset
- Removed invalid values and handled outliers
- Performed statistical analysis
- Built multiple data visualizations
- Trained a machine learning model (Random Forest Regressor)

## Key Concepts
- Age of Information (AoI)
- Transmission probability
- Packet loss probability
- Channel quality
- AoI vs reliability trade-off

## Data Analysis
- Cleaned dataset (removed NaN and infinite values)
- Performed feature engineering
- Generated visualizations:
  - Scatter plots (AoI vs transmission probability)
  - Box plots (AoI & packet loss by traffic type)
  - Correlation heatmap

## Machine Learning Model
- Model: Random Forest Regressor
- Target: Age of Information
- Evaluation metrics:
  - RMSE ≈ 6.85
  - R² ≈ 0.996

## Key Insights
- Channel quality is the strongest factor affecting AoI
- Packet loss significantly increases AoI
- Higher transmission probability reduces AoI
- There is a clear trade-off between reliability and data freshness

## What I Learned
This lab helped me understand how real-world networks balance latency and reliability. I also gained experience applying machine learning to network optimization problems.

## Files Included
- Jupyter Notebook (.ipynb)
- PDF Report (.pdf)
