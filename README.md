# 🏠 House Price Prediction using Machine Learning

> **Summerix Global AI & ML Internship – Task 3**

An end-to-end Machine Learning project that demonstrates **data preprocessing, regression modeling, cross-validation, hyperparameter tuning, overfitting analysis, and model optimization** using the California Housing Dataset.

---

## 🚀 Project Overview

This project focuses on predicting California house prices using multiple regression algorithms. Different models were trained, evaluated, compared, and optimized to build a reliable prediction model with strong generalization performance.

The project follows an industry-standard machine learning workflow and emphasizes proper model validation before deployment.

---

## ✨ Features

- 📊 Data Preprocessing
- ⚙️ Feature Scaling using StandardScaler
- 🤖 Multiple Regression Models
- 📈 Model Evaluation (MAE, RMSE, R²)
- 🔄 5-Fold Cross Validation
- 🎯 Hyperparameter Tuning using GridSearchCV
- 📉 Overfitting Analysis
- 🏆 Final Model Selection
- 💾 Model Serialization using Joblib

---

# 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Joblib
- Jupyter Notebook

---

# 📂 Dataset

**California Housing Dataset**

**Target Variable:**
- Median House Value

**Features:**
- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

---

# 🤖 Models Implemented

- Linear Regression
- Ridge Regression
- Decision Tree Regression
- Tuned Decision Tree (GridSearchCV)

---

# 📊 Final Performance

| Model | Test RMSE | Test R² |
|--------|----------:|---------:|
| Linear Regression | 0.7456 | 0.5758 |
| Ridge Regression | 0.7456 | 0.5758 |
| Decision Tree Regression | 0.7242 | 0.5997 |
| 🏆 Tuned Decision Tree | **0.6387** | **0.6887** |

The tuned Decision Tree achieved the best predictive performance after hyperparameter tuning using **GridSearchCV**.

---

# 🔄 Cross Validation Results

| Model | Mean CV RMSE |
|--------|-------------:|
| Linear Regression | 0.7205 |
| Ridge Regression | 0.7205 |
| Decision Tree Regression | **0.7127** |

The Decision Tree Regression model achieved the best baseline cross-validation performance.

---

# ⚙️ Best Hyperparameters

```python
criterion = "squared_error"
max_depth = 10
min_samples_leaf = 4
min_samples_split = 2
```

---

# 📷 Project Results

## 🏆 Final Model Comparison

![Model Comparison](images/model_comparison.png)

---

## 📉 RMSE Comparison

![RMSE Comparison](images/rmse_comparison.png)

---

## 📊 Feature Importance

![Feature Importance](images/feature_importance.png)

---

## 🎯 Actual vs Predicted

![Actual vs Predicted](images/actual_vs_predicted.png)

---

## 🔄 Cross Validation Results

![Cross Validation](images/cross_validation_results.png)

---

## ⚙️ GridSearchCV Results

![GridSearchCV](images/gridsearch_results.png)

---

# 💾 Saved Models

- **best_model_task3.pkl** → Final optimized production model.
- **best_model.pkl** → Retained for backward compatibility.
- **scaler.pkl** → StandardScaler used during preprocessing.

---

# 📁 Project Structure

```text
house-price-prediction-model-validation/

│── AI_ML_Task3_Model_Validation_Tuning.ipynb
│── README.md
│── requirements.txt
│── best_model_task3.pkl
│── best_model.pkl
│── scaler.pkl
│
└── images/
    ├── model_comparison.png
    ├── rmse_comparison.png
    ├── feature_importance.png
    ├── actual_vs_predicted.png
    ├── cross_validation_results.png
    └── gridsearch_results.png
```

---

# 🎯 Key Learning Outcomes

- Machine Learning Workflow
- Data Preprocessing
- Regression Analysis
- Model Evaluation
- Cross Validation
- Hyperparameter Tuning
- GridSearchCV
- Overfitting Detection
- Model Generalization
- Model Serialization

---

# 🔮 Future Improvements

- Random Forest & XGBoost Comparison
- Web Deployment using Streamlit
- Real-time Property Price Prediction
- Model Explainability with SHAP
- Automated ML Pipeline

---

# 👩‍💻 Author

**Bhakti Unhale**

🎓 B.Tech CSE (Artificial Intelligence & Analytics)  
🏫 MIT Art, Design and Technology University

🔗 GitHub: https://github.com/bhaktibytes

---

⭐ If you found this project helpful, consider giving it a **Star**!