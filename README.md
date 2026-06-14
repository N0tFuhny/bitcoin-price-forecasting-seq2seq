# ₿ Bitcoin Price Forecasting using Seq2Seq Deep Learning

### Multivariate Multi-Horizon Time Series Forecasting with TensorFlow

<p align="center">

<img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow" />
<img src="https://img.shields.io/badge/Forecasting-Time%20Series-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Seq2Seq-Teacher%20Forcing-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/Multi--Head-Attention-purple?style=for-the-badge" />

</p>

---

## Project Overview

This project implements a Multivariate Multi-Horizon Time Series Forecasting system for Bitcoin price prediction using Deep Learning and Sequence-to-Sequence (Seq2Seq) architectures.

The objective is to forecast future Bitcoin prices across multiple time horizons while capturing temporal dependencies from historical market data.

The project compares a baseline LSTM model against a custom Seq2Seq model trained with Teacher Forcing and evaluates forecasting performance using MAE and RMSE metrics.

---

## Key Highlights

* Multivariate Time Series Forecasting
* Multi-Horizon Prediction
* Sequence-to-Sequence (Seq2Seq) Architecture
* Teacher Forcing Training Strategy
* Custom Multi-Head Attention Layer
* Custom Training Loop with TensorFlow
* Recursive Autoregressive Forecasting
* Horizon Degradation Analysis
* Model Benchmarking and Evaluation

---

## Dataset

Bitcoin historical market data containing multiple features used for forecasting future price movements.

### Data Processing Pipeline

* Feature Engineering
* Correlation Analysis
* Seasonal Decomposition
* ACF & PACF Analysis
* Feature Scaling
* Windowing Strategy
* TensorFlow Dataset Pipeline

---

## Model Architecture

### Baseline Model

* LSTM-based Forecasting Network
* Multi-Horizon Output
* Custom Training Loop

### Advanced Model

* Seq2Seq Encoder-Decoder Architecture
* Teacher Forcing
* Multi-Head Attention
* Layer Normalization
* Dropout Regularization
* Weighted Horizon Loss

---

## Training Strategy

### Custom Components

* Custom Dense Layer
* Custom Layer Normalization
* Custom Dropout Layer
* Custom Multi-Head Attention
* Custom Weighted Horizon Loss

### Optimization

* Adam Optimizer
* Custom Training Steps
* TensorFlow GradientTape
* Early Performance Monitoring

---

## Results

### Forecasting Performance

| Metric | Baseline LSTM | Seq2Seq |
| ------ | ------------- | ------- |
| MAE    | 327.68        | 162.67  |
| RMSE   | 469.40        | 211.40  |

### Improvement

Seq2Seq significantly outperformed the baseline model.

**MAE Improvement:** 50.36%

---

## Evaluation Techniques

* MAE Evaluation
* RMSE Evaluation
* Recursive Forecasting
* Prediction Comparison
* Horizon Error Analysis
* Forecast Visualization

---

## Skills Demonstrated

### Machine Learning

* Time Series Forecasting
* Deep Learning
* Sequence Modeling
* Attention Mechanisms
* Multi-Step Forecasting

### TensorFlow

* Custom Training Loops
* GradientTape
* Model Subclassing
* Custom Layers
* Advanced Model Architecture

### Data Science

* Feature Engineering
* Time Series Analysis
* Statistical Decomposition
* Forecast Evaluation
* Model Benchmarking

---

## Future Improvements

* Transformer-based Forecasting
* Temporal Fusion Transformer (TFT)
* Hyperparameter Optimization
* MLflow Experiment Tracking
* Docker Deployment
* FastAPI Forecasting API
* Real-Time Crypto Forecast Dashboard

---

## Author

Muhammad Rizky Abdillah

Aspiring AI Engineer | Machine Learning Engineer | Deep Learning Enthusiast

LinkedIn: https://linkedin.com/in/rzkyabdlh

GitHub: https://github.com/N0tFuhny
