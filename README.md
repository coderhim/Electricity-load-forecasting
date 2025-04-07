# Electricity Load Forecasting

This project focuses on short-term electricity load forecasting using time series analysis techniques, specifically AutoRegressive Integrated Moving Average (ARIMA) and Long Short-Term Memory (LSTM) networks. The aim is to compare the performance of these models in predicting electricity demand, utilizing the modified Panama dataset from Kaggle.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models Implemented](#models-implemented)
- [Results](#results)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [References](#references)
- [Acknowledgments](#acknowledgments)

## Project Overview

Accurate short-term load forecasting is crucial for efficient energy management and operational planning in the power sector. This project implements and compares two prominent forecasting models:

- **ARIMA**: A classical statistical approach for time series forecasting.
- **LSTM**: A deep learning-based recurrent neural network capable of capturing long-term dependencies in sequential data.

By evaluating these models, the project aims to identify the most effective method for short-term electricity load prediction.

## Dataset

The analysis utilizes the modified Panama electricity load dataset, sourced from Kaggle. This dataset encompasses time-stamped records of electricity consumption, which are essential for training and evaluating the forecasting models.

## Models Implemented

1. **ARIMA**: Implemented in the `MYAuto_ARIMA.ipynb` notebook, this model involves:
   - Time series decomposition to understand underlying patterns.
   - Parameter selection using autocorrelation and partial autocorrelation plots.
   - Model fitting and validation using historical data.

2. **LSTM**: Detailed in the `TEMPEST.ipynb` notebook, this model includes:
   - Data preprocessing, such as normalization and sequence generation.
   - Construction of the LSTM network architecture.
   - Training the network and evaluating its predictive performance.

## Results

Both models were evaluated based on their forecasting accuracy. The comparative analysis provides insights into the strengths and limitations of each approach in the context of electricity load forecasting.

## Getting Started

To replicate or build upon this analysis, follow the steps below.

### Prerequisites

Ensure the following Python libraries are installed:

- `pandas`
- `numpy`
- `matplotlib`
- `statsmodels`
- `tensorflow` or `keras` (for LSTM implementation)
- `jupyter`

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/coderhim/Electricity-load-forecasting.git
