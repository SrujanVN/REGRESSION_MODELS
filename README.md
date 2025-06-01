# 🏡 Predicting California Home Prices Using Regression: Model Benchmarking

This project showcases the use of **eight different regression algorithms** to estimate housing prices in California using the **California Housing dataset**. Developed in Python with `scikit-learn`, it highlights model performance comparison based on standard evaluation metrics and visual insights.

---

## 📘 What is Regression?

Regression is a supervised machine learning approach for predicting continuous values based on given features. It’s used to measure relationships between variables and is vital for forecasting and data interpretation.

---

### 🧭 Supervised vs Unsupervised Learning

**Supervised Learning** involves labeled data where each input is associated with a known output.

- **Regression** and **Classification** are two key types.

**Unsupervised Learning** doesn’t rely on labeled data, and includes methods like clustering and dimensionality reduction.

Since we aim to predict numeric outcomes (like housing prices) from labeled data, this project uses **regression**, a supervised learning technique.

---

## 🔍 Purpose of Regression

Regression enables us to:

- Forecast values (e.g., future home prices, economic indicators)
- Evaluate variable influence (e.g., how location affects pricing)
- Fill in missing data (e.g., estimates in incomplete records)
- Perform data trend analysis

---

## 📦 Common Applications

- 🏘️ **Real Estate** – Price estimation of properties  
- 💰 **Finance** – Stock and investment value prediction  
- 🏥 **Healthcare** – Recovery time or health outcome prediction  
- 🛒 **Retail** – Demand estimation  
- 📊 **Marketing** – Predicting customer retention or sales ROI  
- ⚙️ **Engineering** – Predictive maintenance and sensor data analysis

---

## 🛠️ Types of Regression Techniques

- **Linear Regression** – Simple linear relationship modeling  
- **Polynomial Regression** – Captures curves and non-linear patterns  
- **Ridge/Lasso Regression** – Regularized linear models to handle overfitting  
- **ElasticNet** – A balance of L1 and L2 regularization  
- **Decision Tree** – Non-linear, rule-based structure  
- **Random Forest** – Ensemble of multiple decision trees  
- **Support Vector Regressor (SVR)** – Margin-based predictions, outlier resistant

---

## 📊 Overview

Steps covered in this notebook:

- Load and inspect the California Housing data  
- Clean and prepare the dataset  
- Train eight regression models  
- Evaluate each model using **R² Score** and **Mean Squared Error (MSE)**  
- Visualize and compare results using plots

---

## 🧠 Models Compared

| Model Name              | Description                              |
|------------------------|------------------------------------------|
| Linear Regression       | Basic linear predictor                   |
| Ridge Regression        | Adds L2 regularization                   |
| Lasso Regression        | Adds L1 regularization                   |
| ElasticNet Regression   | Combines L1 and L2 penalties             |
| Decision Tree           | Hierarchical rule-based model            |
| Random Forest           | Averaged ensemble of trees               |
| Polynomial Regression   | Adds polynomial features for non-linearity |
| Support Vector Regressor| Margin-focused regression technique      |

---

## 📁 File Structure

## 🚀 Getting Started
1. Clone the Repository
```bash
git clone https://github.com/your-username/california-housing-regression.git
cd california-housing-regression
```
2. Install Dependencies
Create a virtual environment (optional but recommended), and install the required packages:

```bash
pip install -r requirements.txt
```
If requirements.txt is not available, manually install:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🧪 How to Use
Run the notebook:

```bash
jupyter notebook RegressionTypes.ipynb
```
Or if you're using VS Code or JupyterLab, simply open and run all cells.

## 📈 Visualizations Included 
1. Feature Importance (Random Forest)
2. Actual vs Predicted Values
3. Bar Charts for R² Score and MSE Comparison

## ✅ Results Snapshot
All models are evaluated on a reserved test dataset. Random Forest and other ensemble methods generally outperform simpler linear models for this housing dataset.


## 📌 Dataset Source
We use the built-in fetch_california_housing() from sklearn.datasets, which provides housing data based on demographics and geographic info from California districts.

## 🙌 Acknowledgments
1. <a href="https://scikit-learn.org/stable/">scikit-learn</a>
2. <a href="https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html">California Housing Dataset</a>
