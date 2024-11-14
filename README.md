# Time Series Forecasting and Tabular Data Generation with TimeGPT, Tabula9, and Relational Deep Learning

This repository contains Colab notebooks and run artifacts for exploring **TimeGPT**, **Tabula9**, and **Relational Deep Learning (RDL)** using **RelBench**. The project involves timeseries forecasting, synthetic data generation, and GNN-based modeling for tabular prediction tasks, with a detailed video presentation explaining the code and results.

## Project Overview

### 1. TimeGPT
- **Multivariate and Long-Horizon Forecasting**: Use TimeGPT for both short and long-term predictions on timeseries data.
- **Fine-Tuning with Custom Data**: Customize TimeGPT by fine-tuning on user-provided timeseries data.
- **Anomaly Detection**: Identify anomalies within timeseries data.
- **Energy Demand Forecasting**: Forecast energy demand based on historical data.
- **Bitcoin Price Prediction**: Predict Bitcoin prices using timeseries forecasting.

### 2. Tabula9
- **Synthetic Data Generation**: Generate synthetic data for real-world datasets.
- **Zero-Shot Inference**: Demonstrate zero-shot inference capability with a Tabula model.

### 3. Relational Deep Learning (RDL) and RelBench
- **GNN-Based Tabular Prediction**: Train a Graph Neural Network (GNN) for tabular prediction using RelBench, with a focus on evaluating model performance metrics.

## Repository Structure

```plaintext
.
├── TimeGPT/
│   ├── Multivariate_Forecasting.ipynb
│   ├── Long_Horizon_Forecasting.ipynb
│   ├── Fine_Tuning_TimeGPT.ipynb
│   ├── Anomaly_Detection.ipynb
│   ├── Energy_Forecasting.ipynb
│   └── Bitcoin_Prediction.ipynb
│
├── Tabula9/
│   ├── Synthetic_Data_Generation.ipynb
│   └── Zero_Shot_Inference.ipynb
│
├── Relational_Deep_Learning/
│   └── GNN_Tabular_Prediction_RelBench.ipynb
│
└── README.md
