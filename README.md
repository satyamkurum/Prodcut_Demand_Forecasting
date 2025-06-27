
# Product Demand Forecasting

This project predicts future product demand using historical sales data and machine learning techniques. It helps optimize inventory management, reduce overstock or stockouts, and improve decision-making for supply chain operations.


## Overview

This repository contains a full notebook implementation for demand forecasting. It includes:
- Data loading & cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model building (Linear Regression, XGBoost, etc.)
- Model evaluation and forecasting


## Project Structure

Demand Forecasting Project.ipynb   # Main notebook with code and results
Sales_Data.csv                     # Dataset with historical sales
README.md                          # Project documentation


## Features

- Time series and trend analysis
- Automated data preprocessing using a custom `EasyPreProcessing` class
- Multiple ML models for comparison
- Valuation metrics: RMSE, MAE, MAPE
- Forecast visualization and insights

## Technologies Used

- Python 3.x
- NumPy
- Pandas
- Seaborn
- Matplotlib
- scikit-learn
- XGBoost
- Custom Preprocessor: `EasyPreProcessing`


## Workflow

1. **Data Cleaning & Wrangling**  
   Handle missing values, duplicates, and ensure proper data types (especially dates).

2. **EDA (Exploratory Data Analysis)**  
   Visualize demand patterns, seasonality, trends, and relationships.

3. **Feature Engineering**  
   Generate lag features, moving averages, and time-based breakdowns.

4. **Modeling**  
   Train models using:
   - Linear Regression
   - XGBoost Regressor

5. **Evaluation**  
   Use RMSE, MAE, and MAPE to validate prediction accuracy.

6. **Visualization**  
   Plot actual vs predicted demand for interpretability.


## Sample Results 

| Model         | RMSE   | MAE    | MAPE (%) |
|---------------|--------|--------|----------|
| Linear Reg.   | 120.34 | 95.21  | 8.7%     |
| XGBoost       | 98.12  | 78.33  | 6.1%     |


## Get Start

### 1. Clone the repository

```bash
git clone https://github.com/satyamkurum/Product_Demand_Forecasting.git
cd Product_Demand_Forecasting
```

### 2. Install dependencies

```bash
pip install -r requirement.txt
```

### 3. Launch the notebook

Open Jupyter Notebook or VS Code and run:

```bash
jupyter notebook "Demand Forecasting Project.ipynb"
```

## 📜 License

This project is licensed under the [MIT License](LICENSE).


## Author

**Satyam Kurum**  
_Data Science & AI Enthusiast_  
 [LinkedIn](https://linkedin.com/in/satyamkurum) | [GitHub](https://github.com/satyamkurum)


> _If you found this project helpful, feel free to ⭐️ star the repo and fork it for your own analysis!_
