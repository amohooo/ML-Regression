# CAB420 Project - Machine Learning Models for Socio-Economic Crime Prediction

## 📘 Overview

This project is part of **CAB420: Machine Learning** at QUT. It focuses on applying and evaluating different regression models (Linear, Ridge, and LASSO) to predict **violent crime rates per capita** using **socio-economic data** from the 1990 US Census.

The project demonstrates practical application of:
- Preprocessing techniques
- Linear and regularised regression
- Model tuning and evaluation
- Diagnostic plotting
- Ethical consideration in modelling real-world data

---

## 🔍 Problem Statement

Given socio-economic attributes of US communities, predict the number of violent crimes per capita using various regression models and compare their performance.

---

## 🧠 What I Learned

Through this project, I have gained proficiency in:
- 🧮 **Linear, Ridge, and LASSO Regression** using both `statsmodels` and `sklearn`
- 🧼 **Data Preprocessing**, including standardization and feature selection
- 📊 **Model Evaluation** using RMSE and R² score on training, validation, and test datasets
- 🧪 **Hyperparameter Tuning** via grid search (especially for regularization parameter λ)
- 📈 **Model Diagnostics**: Residual plots, Q-Q plots, histograms, and correlation heatmaps
- 🤔 **Ethical considerations** when using sensitive socio-economic data

---

## 🧰 Tools and Libraries Used

- `numpy`, `pandas` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `statsmodels` – Regression and diagnostics
- `sklearn` – Alternative regressors, metrics
- `scipy` – Statistical analysis

---

## 🛠️ Key Functionalities

- Load and preprocess training, validation, and testing datasets
- Train models:
  - Linear Regression
  - Ridge Regression (L2 regularization)
  - LASSO Regression (L1 regularization)
- Select optimal λ using validation RMSE for Ridge/LASSO
- Evaluate model performance on test data
- Visualize:
  - Residual diagnostics
  - Correlation heatmaps
  - RMSE vs λ
  - Coefficient shrinkage
- Standardize and inverse-transform predictions for fair evaluation
- Discuss ethical limitations and concerns in socio-economic modelling

---

## ✅ Results Summary

- Linear Regression serves as a baseline.
- Ridge Regression offers improved generalization through regularization.
- LASSO helps in feature selection by shrinking irrelevant coefficients to zero.
- Best model selection based on:
  - **RMSE on test set**
  - **Residual analysis**
  - **Simplicity and interpretability**

---

## ⚖️ Ethical Considerations

Modelling socio-economic and crime-related data requires awareness of:
- Potential bias and discrimination in the dataset
- Misuse or overinterpretation of the model outputs
- Importance of fairness and accountability in deploying predictive systems

---

## 📌 Future Improvements

- Introduce feature selection and PCA for dimensionality reduction
- Extend models with nonlinear kernels or ensemble methods
- Incorporate confidence intervals or uncertainty quantification
- Build an interactive dashboard for better interpretation

---

## 🚀 How to Run

1. Clone the repo
2. Install requirements: `pip install -r requirements.txt` *(if you extract all dependencies)*
3. Run the script or notebook to reproduce analysis and plots

---

## 📬 Contact

If you have any questions, feel free to reach out!

**Mohan Hao**  
Machine Learning Student, QUT  
📧 imhaom@gmail.com

---
