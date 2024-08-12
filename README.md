

# House Price Prediction Using XGBoost Regressor

## Overview

This project involves predicting house prices using machine learning techniques. The dataset used is the California Housing Dataset, which includes various features related to housing and demographic information. The goal is to build and evaluate a predictive model using the XGBoost Regressor to estimate house prices.

## Table of Contents

- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Results](#results)
- [Visualizations](#visualizations)


## Project Description

The project uses the California Housing Dataset to predict house prices based on various features. The dataset is processed, and an XGBoost Regressor model is trained and evaluated. Key performance metrics such as R-squared error and Mean Absolute Error are used to assess the model's accuracy.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

## Dataset

- **Source:** California Housing Dataset
- **Features:** Includes metrics like average rooms per household, population density, median income, etc.
- **Target Variable:** House price

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Pkanagalakshmi/house-price-prediction.git
   cd house-price-prediction
   ```

2. **Create a Virtual Environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Required Libraries:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare Data:**
   The dataset is fetched from `sklearn.datasets`. Ensure the `fetch_california_housing` function is used to load the dataset.

2. **Run the Script:**
   ```bash
   python main.py
   ```

   The script performs the following tasks:
   - Loads and preprocesses the data.
   - Trains an XGBoost Regressor model.
   - Evaluates the model using training and test data.
   - Outputs performance metrics and visualizations.

## Results

- **Training Data Evaluation:**
  - R-squared Error
  - Mean Absolute Error

- **Test Data Evaluation:**
  - R-squared Error
  - Mean Absolute Error

## Visualizations

- **Heatmap:** Displays correlation between features and the target variable.
- **Scatter Plots:** Visualize the relationship between actual and predicted house prices.
