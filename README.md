# House Price Prediction

## Project Overview

This project aims to predict house prices using Machine Learning techniques and identify the factors that most influence property values.

The analysis was performed on a real-world housing dataset obtained from Kaggle. Two regression models were trained and compared:

- Linear Regression
- Random Forest Regressor

The project also includes exploratory data analysis, feature engineering, visualization, and business recommendations.

---

## Dataset

Source:

https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

Dataset contains information such as:

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Parking
- Air Conditioning
- Furnishing Status
- House Price

---

## Project Workflow

### 1. Data Cleaning

- Checked missing values
- Removed duplicates
- Converted categorical variables into numerical form
- Applied One-Hot Encoding where required

### 2. Exploratory Data Analysis

Created visualizations to understand:

- House Price Distribution
- Feature Correlations
- Impact of Main Road Connectivity

### 3. Model Building

Models Used:

1. Linear Regression
2. Random Forest Regressor

Train-Test Split:

- 80% Training
- 20% Testing

---

## Model Performance

### Linear Regression

| Metric | Value |
|----------|----------|
| MAE | 970,043 |
| RMSE | 1,324,507 |
| R² Score | 0.653 |

### Random Forest Regressor

| Metric | Value |
|----------|----------|
| MAE | 1,014,947 |
| RMSE | 1,399,769 |
| R² Score | 0.612 |

### Best Model

Linear Regression performed better on this dataset.

---

## Key Findings

- Area was the most influential factor affecting house price.
- Bathrooms, air conditioning, parking spaces, and stories also significantly impacted price.
- Most houses belonged to the mid-price segment.
- Houses connected to a main road generally achieved higher prices.
- Main-road access was common among premium-priced properties.
- Linear Regression outperformed Random Forest on this dataset.

---

## Business Recommendation

Real estate businesses should focus not only on property size but also on features such as road connectivity, bathrooms, parking facilities, and air conditioning. Properties with better accessibility and amenities consistently achieved higher prices and should be prioritized in future developments and marketing campaigns.

---

## Visualizations

### House Price Distribution

![Distribution](charts/House-Price_Distribeution.png)

### Correlation Heatmap

![Heatmap](charts/Heatmap.png)

### Impact of Main Road Access

![Main Road](charts/Impact_main_road_connectivity.png)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Author

Shubham Meena
B.Tech Chemical Engineering
IIT (BHU) Varanasi
Aspiring Data Scientist
