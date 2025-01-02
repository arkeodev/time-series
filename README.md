# Time Series Analysis Repository

## Introduction

This repository provides a comprehensive collection of time series analysis techniques, from traditional statistical methods to modern deep learning approaches. It serves as both a learning resource and a practical toolkit for working with time-dependent data.

## Repository Structure

The repository is organized into three main sections:

### 1. Statistical Time Series Analysis

A comprehensive collection of notebooks covering fundamental to advanced statistical methods:

- Basic Concepts (Introduction, Autocorrelation, Covariance)
- Data Preparation (Stationarity, Normalization)
- Model Selection (AIC vs BIC)
- Classical Models:
  - Autoregressive (AR)
  - Moving Average (MA)
  - ARMA, ARIMA, ARIMAX
  - SARIMAX
  - ARCH/GARCH
  - Auto-ARIMA

### 2. Meta Prophet Analysis

Implementation of Meta's Prophet package for time series forecasting, particularly effective for:

- Data with strong seasonal patterns
- Missing data handling
- Outlier management
- Multiple seasonality patterns

### 3. Deep Learning Approaches

Advanced neural network architectures for time series:

- CNN-LSTM hybrid models
- Deep learning specific considerations for time series
- Neural network architecture selection

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/time-series.git
cd time-series
```

2.Install dependencies:

```bash
pip install -r requirements.txt
```

3.Launch Jupyter:

```bash
jupyter notebook
```

4.Start with `Statistical_Time_Series_Analysis/01-introduction-to-time-series.ipynb` for a structured learning path.

## Learning Path

For optimal learning, follow this recommended sequence:

1. Start with Statistical Analysis (01-introduction through 18-auto-ARIMA)
2. Explore Prophet for automated forecasting
3. Advance to deep learning approaches

## Future Developments

- Transformer-based architectures for time series
- Probabilistic forecasting methods
- Advanced deep learning architectures (Temporal Fusion Transformers, N-BEATS)
- Real-world case studies and applications

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## References

- [Forecasting: Principles and Practice](https://otexts.com/fpp3/)
- [Time Series Analysis and Its Applications](https://www.stat.pitt.edu/stoffer/tsa4/)
- [Prophet Documentation](https://facebook.github.io/prophet/)
- [Deep Learning for Time Series Forecasting](https://www.tensorflow.org/tutorials/structured_data/time_series)
