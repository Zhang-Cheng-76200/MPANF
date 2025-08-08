# Movement-Prediction–Adjusted Naive Forecast (MPANF)

## Overview
This repository contains the implementation of the **Movement-Prediction–Adjusted Naive Forecast (MPANF)** method for **financial time series forecasting**.  
The MPANF is a second-stage forecasting approach that integrates **movement (directional) predictions** with the **naive forecast** to improve point forecasting accuracy.

Key features:
- Combines binary movement predictions (up/down) with naive forecasts.
- Works with any movement prediction model.
- Designed for one-step-ahead forecasting of financial time series.
- Applicable to out-of-sample evaluation.
- Supported by both **theoretical analysis** and **empirical experiments**.

📄 **Read the paper on arXiv:** [https://doi.org/10.48550/arXiv.2406.14469]

---

## Requirements

- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

Install the dependencies:
```bash
pip install -r requirements.txt

