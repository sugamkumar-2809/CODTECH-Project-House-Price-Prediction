CODTECH INTERN ID - CT-1333

# 🏠 House Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

# 📌 Project Overview

This project predicts house prices using Machine Learning techniques by analyzing property characteristics such as area, number of bedrooms, bathrooms, floors, year built, location, condition, and garage availability.

The project demonstrates an end-to-end Machine Learning workflow, including:

* Data Collection
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Feature Engineering
* Pipeline Construction
* Model Selection
* Cross Validation
* Hyperparameter Tuning
* Model Evaluation
* Prediction System

---

# 🎯 Objective

Build a Machine Learning model capable of estimating house prices based on various house attributes and compare multiple regression algorithms to identify the most suitable approach.

---

# 📊 Dataset Information

### Dataset Size

* Records: **2,000 Houses**
* Features: **10 Columns**

### Features

| Feature   | Description                      |
| --------- | -------------------------------- |
| Id        | Unique House Identifier          |
| Area      | House Area                       |
| Bedrooms  | Number of Bedrooms               |
| Bathrooms | Number of Bathrooms              |
| Floors    | Number of Floors                 |
| YearBuilt | Construction Year                |
| Location  | Downtown, Urban, Suburban, Rural |
| Condition | Excellent, Good, Fair, Poor      |
| Garage    | Garage Availability              |
| Price     | Target Variable                  |

---

# 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

### Development Environment

* Jupyter Notebook
* Google Colab
* VS Code

---

# 📂 Project Structure

```text
House_Price_Prediction/
│
├── House Price Prediction Dataset.csv
├── Project2_House_Price_Prediction.ipynb
├── README.md
│
└── outputs/
    ├── correlation_heatmap.png
    ├── distributions.png
    ├── boxplots.png
    └── residual_plots.png
```

---

# 🔄 Machine Learning Workflow

```text
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Preprocessing Pipeline
        ↓
Train-Test Split
        ↓
Model Selection
        ↓
Cross Validation
        ↓
Hyperparameter Tuning
        ↓
Final Model Training
        ↓
Prediction System
```

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset Information
* Missing Value Analysis
* Duplicate Detection
* Descriptive Statistics
* Distribution Analysis
* Correlation Heatmap
* Outlier Detection
* Categorical Feature Distribution
* Target Variable Distribution

---

# ⚙️ Data Preprocessing

## Numerical Features

* Median Imputation
* Standard Scaling

## Categorical Features

* Most Frequent Imputation
* One-Hot Encoding

## Preprocessing Pipeline

* SimpleImputer
* StandardScaler
* OneHotEncoder
* ColumnTransformer
* Pipeline API

---

# 🤖 Models Implemented

The following regression models were evaluated:

### Linear Regression

### Ridge Regression

### Lasso Regression

### Random Forest Regressor

### HistGradientBoostingRegressor

---

# 🔍 Cross Validation

The project uses:

* 5-Fold Cross Validation
* RMSE Evaluation
* MAE Evaluation
* R² Score Evaluation

---

# ⚡ Hyperparameter Tuning

GridSearchCV was used to optimize the HistGradientBoostingRegressor.

### Tuned Parameters

* Learning Rate
* Maximum Depth
* Maximum Leaf Nodes
* Minimum Samples Leaf
* L2 Regularization

---

# 📊 Model Performance

## Baseline Linear Regression

| Metric   | Value      |
| -------- | ---------- |
| RMSE     | 274,246.37 |
| MAE      | 242,867.45 |
| R² Score | 0.010      |

---

## Final HistGradientBoosting Model

### Training Performance

| Metric   | Value      |
| -------- | ---------- |
| RMSE     | 110,586.32 |
| MAE      | 90,594.70  |
| R² Score | 0.839      |

### Testing Performance

| Metric   | Value      |
| -------- | ---------- |
| RMSE     | 308,911.22 |
| MAE      | 259,971.10 |
| R² Score | -0.227     |

---

# 🔮 Predictive System

Example Input:

```python
predict_house_price(
    area=2500,
    bedrooms=3,
    bathrooms=2,
    floors=2,
    year_built=2015,
    location="Downtown",
    condition="Excellent",
    garage="Yes"
)
```

### Predicted House Price

```text
₹492,558.03
```

---

# 📊 Visualizations Included

* Categorical Count Plots
* Target Distribution Histogram
* Numerical Feature Distributions
* Boxplots for Outlier Detection
* Correlation Heatmap
* Residual Plot
* Residual Distribution Plot

---

# 💡 Key Insights

✔ Dataset contains both numerical and categorical features.

✔ No missing values or duplicate records were found.

✔ Data preprocessing pipelines significantly simplified model training.

✔ Multiple regression models were evaluated and compared.

✔ HistGradientBoostingRegressor was selected after hyperparameter tuning.

✔ The project demonstrates a complete Machine Learning workflow from data preprocessing to prediction.

---

# 🎓 Learning Outcomes

This project helped in understanding:

* Data Preprocessing Pipelines
* Exploratory Data Analysis
* Regression Algorithms
* Model Evaluation Metrics
* Cross Validation
* Hyperparameter Tuning
* Scikit-Learn Pipelines
* Predictive Systems Development

---

# 🔮 Future Enhancements

* XGBoost Regressor
* LightGBM Integration
* Feature Selection Techniques
* Advanced Ensemble Models
* Model Deployment using Flask
* Streamlit Dashboard
* REST API Integration
* Real-Time House Price Prediction System

---


# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

### 🏠 Predicting Property Prices Through Data and Machine Learning 🚀
