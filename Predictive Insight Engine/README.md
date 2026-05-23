# 🏠 Predictive Insight Engine

## 📌 House Price Prediction Using Supervised Learning

A professional end-to-end regression project built in Jupyter Notebook to analyze and predict house prices using multiple supervised learning techniques. This project combines theory, visual analysis, model building, evaluation, optimization, and diagnostics in a single structured workflow.

---

## ✨ Project Highlights

- 📊 Real-estate dataset with **4,200 records**
- 🧹 Clear **data understanding and preparation**
- 📈 **Simple Linear Regression** using `area_sqft`
- 🏘️ **Multiple Linear Regression** using all relevant features
- 📐 **Polynomial Regression** comparison
- ⚙️ **Batch, Stochastic, and Mini-Batch Gradient Descent**
- 🧠 **Bias-Variance analysis and model diagnostics**
- 📓 Fully documented in a **Jupyter Notebook**

---

## 🎯 Project Objective

The goal of this project is to build a predictive system for estimating house prices based on property-related features such as area, bedrooms, bathrooms, location score, age of property, and amenities.  

This notebook was completed as a supervised learning project with a strong focus on:

- understanding regression concepts
- implementing models step by step
- comparing model performance
- analyzing overfitting and underfitting
- interpreting the business meaning of the results

---

## 📂 Dataset Information

**Dataset file:** `data/real_estate_house_price_dataset.csv`

### Features used in the project

- `area_sqft`
- `bedrooms`
- `bathrooms`
- `location_score`
- `age_years`
- `distance_city_km`
- `lot_size_sqft`
- `has_garage`
- `has_pool`
- `renovation_years_ago`

### Target variable

- `house_price_inr`

### Additional column

- `house_id` used as an identifier only

---

## 🛠️ Tools and Libraries

- `Python`
- `Jupyter Notebook`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

---

## 📘 Project Workflow

### Part A: Conceptual Understanding

- Supervised Learning Algorithms
- Regression vs Classification
- Simple Linear Regression
- Assumptions of Linear Regression
- Bias-Variance Trade-Off
- Overfitting and Underfitting

### Part B: Dataset Understanding and Preparation

- Identified independent and dependent variables
- Studied feature relationships with house price
- Split data into training and testing sets

### Part C: Simple Linear Regression

- Built a baseline regression model using `area_sqft`
- Plotted the regression line
- Checked residual behavior and assumptions

### Part D: Model Evaluation Metrics

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R² Score

### Part E: Multiple Linear Regression

- Trained a multi-feature regression model
- Compared it with simple linear regression
- Interpreted the performance gain

### Part F: Polynomial Regression

- Tested polynomial models of degree 2 and 3
- Compared them visually and numerically
- Checked for signs of underfitting and overfitting

### Part G: Gradient Descent Optimization

- Implemented Batch Gradient Descent
- Implemented Stochastic Gradient Descent (SGD)
- Implemented Mini-Batch Gradient Descent
- Compared convergence speed and final performance

### Part H: Bias-Variance and Model Diagnostics

- Compared bias and variance across models
- Evaluated train-test performance gaps
- Identified the best balanced model

### Part I: Final Analysis and Reporting

- Summarized the best model
- Explained optimization impact
- Discussed practical business interpretation

---

## 📊 Key Results

### Model comparison summary

| Model | Test RMSE | Test R² | Key Insight |
|---|---:|---:|---|
| Simple Linear Regression | 8.18e+06 | 0.5625 | Good baseline, but limited because it uses only one feature |
| Multiple Linear Regression | 3.55e+06 | 0.9178 | Best overall model with strong predictive performance |
| Polynomial Regression (Degree 3) | 8.18e+06 | 0.5629 | Only a slight improvement over simple linear regression |
| Batch Gradient Descent | 3.55e+06 | 0.9177 | Smooth convergence and strong final accuracy |
| Stochastic Gradient Descent | 3.81e+06 | 0.9051 | More noisy updates and slightly weaker final score |
| Mini-Batch Gradient Descent | 3.57e+06 | 0.9169 | Fast, stable, and very close to batch performance |

### Key findings

- ✅ `area_sqft` showed the strongest positive relationship among the core features.
- ✅ **Multiple Linear Regression** reduced test RMSE by about **56.64%** compared to Simple Linear Regression.
- ✅ Polynomial regression did not produce a major performance jump on this dataset.
- ✅ **Multiple Linear Regression** gave the best balance of bias and variance.
- ✅ Batch and Mini-Batch Gradient Descent converged effectively after feature scaling.

---

## 🧠 Final Conclusion

The strongest model in this project is **Multiple Linear Regression** because house price depends on several features, not only area. It captures the effect of property size, location quality, amenities, distance from the city, and house age far better than the one-feature models.

From a business point of view:

- 📍 better location score increases price
- 🏡 larger area and more rooms increase price
- 🚗 amenities such as garage and pool add value
- 🕒 older properties and longer city distance tend to reduce price

Overall, this project shows that a well-structured regression workflow can provide both **strong prediction accuracy** and **meaningful real-estate insights**.

---

## 🖼️ Project Snapshots

### 📝 Notebook Preview

<p align="center">
  <img src="screenshots/Screenshot%202026-05-23%20151645.png" alt="Notebook preview" width="90%">
</p>

### 📊 Part B: Data Understanding and Preparation

<p align="center">
  <img src="screenshots/1%20B-%20data%20u%20%26%20p.png" alt="Data understanding and preparation" width="95%">
</p>

### 📈 Part C: Simple Linear Regression

<p align="center">
  <img src="screenshots/2%20C-%20simple%20linear%20regg%201.png" alt="Simple linear regression plot" width="48%">
  <img src="screenshots/2%20C-%20simple%20linear%20regg%202.png" alt="Simple linear regression residual diagnostics" width="48%">
</p>

### 📏 Part D: Model Evaluation Metrics

<p align="center">
  <img src="screenshots/3%20D-%20model%20evalution%20metrix.png" alt="Model evaluation metrics" width="85%">
</p>

### 🏘️ Part E: Multiple Linear Regression

<p align="center">
  <img src="screenshots/4%20E-%20MLR%201.png" alt="Multiple linear regression metrics" width="44%">
  <img src="screenshots/4%20E-%20MLR%202.png" alt="Multiple linear regression comparison" width="52%">
</p>

### 📐 Part F: Polynomial Regression

<p align="center">
  <img src="screenshots/5%20F-%20Polynomial%20regg%201.png" alt="Polynomial regression metrics" width="44%">
  <img src="screenshots/5%20F-%20Polynomial%20regg%202.png" alt="Linear vs polynomial regression" width="52%">
</p>

### ⚙️ Part G: Gradient Descent Optimization

<p align="center">
  <img src="screenshots/6%20G-%20gradient%20desc%20optimization.png" alt="Gradient descent optimization" width="70%">
</p>

### 🧪 Part H: Bias-Variance and Model Diagnostics

<p align="center">
  <img src="screenshots/7%20H-%20bies%20var%20%26%20model%20diagonist.png" alt="Bias variance and diagnostics" width="80%">
</p>

---

## 🚀 How to Run the Project

### 1. Open the project folder

Make sure these files are available:

- `real_estate_house_price_project.ipynb`
- `data/real_estate_house_price_dataset.csv`

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy notebook
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open and run

Open `real_estate_house_price_project.ipynb` and run the cells in order from top to bottom.

---

## 📁 Repository Structure

```text
real-estate-house-price-project/
├── data/
│   └── real_estate_house_price_dataset.csv
├── screenshots/
│   ├── 1 B- data u & p.png
│   ├── 2 C- simple linear regg 1.png
│   ├── 2 C- simple linear regg 2.png
│   ├── 3 D- model evalution metrix.png
│   ├── 4 E- MLR 1.png
│   ├── 4 E- MLR 2.png
│   ├── 5 F- Polynomial regg 1.png
│   ├── 5 F- Polynomial regg 2.png
│   ├── 6 G- gradient desc optimization.png
│   ├── 7 H- bies var & model diagonist.png
│   └── Screenshot 2026-05-23 151645.png
├── real_estate_house_price_project.ipynb
└── README.md
```

---

## 📌 Files Included

- 📓 `real_estate_house_price_project.ipynb` — complete notebook with theory, implementation, and analysis
- 🗂️ `real_estate_house_price_dataset.csv` — dataset used for the project
- 🖼️ `screenshots/` — visual outputs and result snapshots
- 📘 `README.md` — project documentation for GitHub

---

## 🙌 Acknowledgement

This project was prepared as a supervised learning assignment focused on regression modeling, optimization, model evaluation, and business interpretation of results.

If you use this project as a reference, keep the notebook structure, results, and explanations properly documented.
