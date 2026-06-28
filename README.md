# Financial Distress Prediction

This project builds a machine learning pipeline to predict financial distress risk among Vietnamese listed companies using quarterly financial statement data.

The goal is to identify firms that may experience financial distress in the next four quarters based on profitability, liquidity, leverage, growth, size, and sector-related financial indicators.

## Colab Notebook

Open the full notebook here:

[Open in Google Colab](https://colab.research.google.com/drive/1PNEAa0KAjC3sdrTR95nz2mqlqVcLMlTk?usp=sharing)

## Project Overview

Financial distress prediction is an important task in credit risk analysis, equity research, and early-warning risk monitoring.  
In this project, financial distress is modeled as a forward-looking classification problem: given a firm's current financial condition, predict whether it will enter financial distress within the next four quarters.

The project includes:

- Data cleaning and financial-sector filtering
- Financial ratio feature engineering
- Missing value and outlier handling
- Forward-looking target construction
- Time-based train/test evaluation
- Model benchmarking across multiple machine learning algorithms
- SHAP-based model interpretation

## Dataset

The dataset contains quarterly financial information for Vietnamese listed firms.

Main data file:

```text
data.xlsx
