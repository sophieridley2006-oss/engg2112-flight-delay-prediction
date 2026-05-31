# ENGG2112 Flight Delay Prediction

## Project Overview
Machine learning pipeline for predicting flight delays at Chicago O'Hare International Airport using BTS flight data, NOAA weather data, and engineered scheduling features.

## Authors
- Sophie Ridley
- Amelia Daunt
- Vittorio Leilani
- Liselotte Thelosen

## Models Evaluated
- Logistic Regression
- Random Forest
- XGBoost
- Multi-Layer Perceptron (MLP)

## Key Findings
- XGBoost achieved the highest PR-AUC (0.340)
- Random Forest achieved the highest AUC-ROC (0.634)
- Pre-departure data can identify flights at elevated delay risk
- Delay duration could not be predicted reliably using pre-departure features alone

## Repository Structure
- data/: datasets
- notebooks/: analysis and modelling code
