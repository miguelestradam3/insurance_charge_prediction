# 💰 Medical Insurance Cost Prediction using XGBoost Regression

This project demonstrates how to build a **regression model** that predicts individual **medical insurance charges** based on personal and health-related attributes. The notebook follows a complete machine learning workflow, including data exploration, preprocessing, categorical encoding, model training, and evaluation using an **XGBoost Regressor**.

The project showcases how gradient boosting can be used to accurately predict continuous values in real-world healthcare datasets.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Data visualization
- Categorical feature encoding
- Train/Test split
- XGBoost Regression model
- Model evaluation using regression metrics
- Prediction of medical insurance charges

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

---

## 📊 Dataset

The project uses the **Medical Cost Personal Dataset**, which contains demographic and health-related information used to estimate medical insurance expenses.

### Features

- Age
- Sex
- Body Mass Index (BMI)
- Number of Children
- Smoking Status
- Region

### Target Variable

- **Medical Insurance Charges**

The goal is to predict the total insurance charges for each individual based on the available features.

---

## 🔍 Exploratory Data Analysis

The notebook includes several exploratory analysis tasks, such as:

- Dataset inspection
- Statistical summaries
- Distribution plots
- Correlation analysis
- Feature relationship visualization
- Identification of categorical and numerical variables

These analyses provide insight into the factors influencing insurance costs.

---

## ⚙️ Data Preprocessing

Before training the model, the notebook performs several preprocessing steps:

- Encode categorical variables using **LabelEncoder**
- Separate input features and target variable
- Split the dataset into training and testing sets

The encoded features include:

- Region
- Sex
- Smoker

---

## 🤖 Machine Learning Model

The project uses an **XGBoost Regressor** with customized hyperparameters, including:

- Learning Rate: **0.1**
- Maximum Depth: **30**
- Number of Estimators: **100**
- Objective Function: **Squared Error Regression**

XGBoost is a powerful gradient boosting algorithm known for its excellent predictive performance on structured datasets.

---

## 📈 Model Evaluation

The regression model is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score (Coefficient of Determination)

These metrics measure how accurately the model predicts medical insurance charges.

---

## 🚀 Getting Started

### Install dependencies

Install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

Run the notebook cells sequentially to reproduce the complete machine learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Explore healthcare datasets
- Encode categorical variables for machine learning
- Train an XGBoost regression model
- Predict continuous numerical values
- Evaluate regression models using industry-standard metrics
- Apply gradient boosting techniques to real-world prediction problems

---

## 🔮 Future Improvements

- Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Compare XGBoost with Linear Regression, Random Forest Regressor, and LightGBM
- Analyze feature importance
- Implement cross-validation
- Build a Streamlit web application for real-time insurance cost predictions
