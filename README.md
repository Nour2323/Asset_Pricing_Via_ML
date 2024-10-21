# Empirical Asset Pricing via Machine Learning

This repository contains the code and data for my master's thesis in Financial Technology, focusing on using machine learning models to predict U.S. stock premiums from 1991 to 2021. The analysis compares various machine learning techniques, including penalized regression, neural networks, and XGBoost, to traditional asset pricing methods.

## Project Overview

The thesis explores the effectiveness of machine learning models in forecasting excess stock returns using a large dataset of 94 firm-specific characteristics and 8 macroeconomic factors. The research aims to improve predictive accuracy, identify key predictors, and analyze risk-adjusted returns.

## Key Features
- **Models Used**: Penalized Regression (Lasso, Ridge), Neural Networks, XGBoost
- **Dataset**: 94 firm characteristics, 8 macroeconomic variables, interaction terms, spanning 1991-2021
- **Validation**: Rolling validation, Diebold-Mariano statistical test for accuracy comparison
- **Performance Metrics**: Adjusted R-squared, variable importance analysis

## Repository Structure
- **/data**: Contains preprocessed data used for the analysis
- **/notebooks**: Jupyter notebooks with model implementation and evaluation
- **/scripts**: Python scripts for data cleaning, model training, and result generation
- **/results**: Includes figures and performance results of the machine learning models

## Getting Started

### Prerequisites
- Python 3.7+
- Required libraries: `pandas`, `scikit-learn`, `tensorflow`, `xgboost`, `numpy`

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/empirical-asset-pricing-ml.git
   cd empirical-asset-pricing-ml
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

### Running the Analysis
1. Preprocess the data:
   ```
   python scripts/preprocess_data.py
   ```
2. Train and evaluate models:
   ```
   python scripts/train_models.py
   ```

## Results
Results from the models, including the variable importance and performance metrics, are saved in the `/results` folder. 

## Contributing
Contributions are welcome! Please feel free to submit issues or pull requests to improve the project.
