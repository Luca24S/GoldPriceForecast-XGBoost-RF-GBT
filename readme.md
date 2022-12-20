# Predicting Commodity Prices using Gradient Boosting Trees

## Overview
This project involves analyzing commodity prices to predict future trends using machine learning models such as Gradient Boosting Trees, Random Forests, and XGBoost. The analysis focuses primarily on gold prices while providing a framework for extending to other commodities or financial datasets.

## Features
1. **Data Preprocessing:**
   - Extracted relevant features such as `Open`, `High`, `Low`, `Close`, and `Volume`.
   - Normalized and split data into training and testing sets.
   
2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics and visualizations (histograms, density plots, correlation matrix, scatter plots).
   - Heatmaps to identify feature relationships.

3. **Machine Learning Models:**
   - Gradient Boosting Trees (GBT)
   - Random Forest Regressor
   - XGBoost Regressor
   - Hyperparameter tuning using RandomizedSearchCV

4. **Evaluation Metrics:**
   - Mean Squared Error (MSE)
   - Variance
   - Model comparison and performance analysis

5. **Time Series Analysis:**
   - Calculated cumulative returns to visualize gold price trends over time.

6. **Decision Tree Modeling:**
   - Applied decision tree models to predict bond prices based on credit ratings, term lengths, and market interest rates.

## Requirements
- Python 3.9.6
- Libraries: 
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `sklearn`
  - `tensorflow`
  - `xgboost`
  - `scipy`
  - `pathlib`

## Usage
1. Clone the repository.
   ```bash
   git clone https://github.com/your-repo/commodity-price-prediction.git
   cd commodity-price-prediction
   ```
2. Install the required packages.
3. Run the main script in a Jupyter Notebook environment.
4. Use the provided dataset (commodity 2000-2022_US Dollar.csv) to train and evaluate models.

## Results

- **Model Performance:**
  - Gradient Boosting Trees demonstrated the best accuracy, with the Mean Squared Error (MSE) lower than the variance of the target variable.
  
- **Cumulative Returns:**
  - Gold price trends were effectively visualized using cumulative returns analysis, providing insights into the growth and volatility of gold over time.

- **Bond Pricing:**
  - Decision Tree models successfully predicted bond prices with high precision, showcasing their applicability in financial product pricing.

## References

1. [Economic Research Paper on Commodities](https://www.econstor.eu/bitstream/10419/239614/1/1760325244.pdf)
2. [IJCRT Paper on Machine Learning](https://ijcrt.org/papers/IJCRT2106681.pdf)