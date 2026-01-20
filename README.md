## AI for Sustainable Energy and Environmental Forecasting

Hybrid Prophet–LSTM Framework for Hourly Energy Consumption Prediction
Design Project – Indian Institute of Information Technology, Vadodara (IIITV)

## Project Overview

Built a hybrid time-series forecasting framework combining Facebook Prophet and LSTM neural networks

Designed for hourly electricity consumption prediction across multiple regions

Integrates statistical trend modeling with deep temporal learning

Focused on improving:

Forecast accuracy

Stability across long horizons

Reliability under uncertainty

Developed as a sustainable energy and environmental intelligence system

## Hybrid Architectures Implemented

# Residual Hybrid (Prophet → LSTM on Residuals)


Modeled baseline trend and seasonality using Prophet

Extracted forecast residual errors

Trained LSTM on residual sequence patterns

Combined Prophet output with LSTM correction signal

Improved nonlinear pattern capture beyond symbolic modeling

# Feature-Augmented Hybrid (Prophet Components → LSTM Inputs)

Decomposed time series using Prophet into:

Trend signals

Seasonal components

Regressor-based features

Injected Prophet components directly into LSTM feature space

Enabled deep learning model to learn interactions between symbolic and temporal features


# Weighted Ensemble Hybrid

Trained Prophet and LSTM as independent predictors

Generated parallel forecast streams

Computed weighted combination based on validation performance

Improved robustness across regional datasets

# Stacking Hybrid Model

Used Prophet and LSTM as base-level models

Trained a meta-model on combined predictions

Learned optimal nonlinear mapping for final forecast output

Improved generalization across seasonal and demand shifts

# Error-Correction Chain (LSTM → Prophet)

Generated primary forecast using LSTM

Modeled systematic LSTM error structure using Prophet

Applied Prophet correction to neural network output

Improved long-term trend alignment and forecast stability

## Data Processing & Feature Engineering

Parsed and standardized regional energy time-series data

Cleaned numeric formatting and missing values

Converted timestamps into Prophet-compatible format

Generated hybrid feature space using:

Raw consumption values

Prophet trend and seasonality components

Statistical features

FFT-based frequency-domain features

LSTM temporal embeddings

Built unified datasets for symbolic and neural learning pipelines

## Evaluation & Reliability Metrics

R² Score

Measures variance explained by hybrid models

RMSE

Quantifies forecast accuracy and error magnitude

PRR (Prediction Reliability Ratio)

Evaluates forecast confidence consistency

CPI (Coverage Probability Index)

Measures uncertainty coverage quality

Residual Entropy

Analyzes randomness and structure in error distributions

## Focused on

Designed and implemented five distinct Prophet–LSTM hybrid architectures

Developed a modular experimentation framework for hybrid forecasting research

Integrated symbolic, statistical, and deep learning features into a unified pipeline

Introduced uncertainty and reliability-focused evaluation metrics

Demonstrated improved stability and generalization for environmental and energy forecasting



IIIT Vadodara ICD – Design Project Team
