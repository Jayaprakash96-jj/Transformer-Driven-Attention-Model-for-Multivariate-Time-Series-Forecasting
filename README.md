# Custom Attention-Based Transformer for Multivariate Time Series Forecasting

## 📌 Project Overview
This project implements a fully custom Transformer-based deep learning model for multivariate time series forecasting. Unlike standard approaches that rely on pre-built Transformer layers, this project builds the core components—including **positional encoding**, **scaled dot-product attention**, **multi-head attention**, and **feed-forward networks**—from scratch using PyTorch.

A synthetic multivariate dataset with trend, seasonality, and noise is programmatically generated to simulate realistic temporal behavior. The performance of the custom Transformer model is compared against two baseline models:

- **LSTM**
- **SARIMA**

This comparison highlights the effectiveness of attention mechanisms in capturing long-range dependencies in high-dimensional time-series data.

---

## 🚀 Features
- Custom implementation of:
  - Positional Encoding  
  - Scaled Dot-Product Attention  
  - Multi-Head Attention  
  - Transformer Blocks  
  - Feed-Forward Network  
- Programmatically generated multivariate time series dataset  
- Baseline comparison with **LSTM** and **SARIMA**  
- Error evaluation using **RMSE** and **MAE**  
- Hyperparameter sweep for:
  - Number of attention heads  
  - Sequence length  

---

## 📂 Project Structure
