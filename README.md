# QSAR-Based LC50 Toxicity Prediction | Machine Learning Bootcamp Project

This repository contains the final project notebook from a Machine Learning Bootcamp. The project focuses on implementing and comparing various supervised learning models to evaluate performance on a regression task involving LC50 (Lethal Concentration 50%) predictions using QSAR features.

🔗 **GitHub Repository**: [qsar-lc50-toxicity-prediction](https://github.com/pooja-pragatika22/qsar-lc50-toxicity-prediction)

## 📌 Project Highlights

- 📊 **Objective**: Predict LC50 values of chemicals using their QSAR (Quantitative Structure–Activity Relationship) descriptors.
- 📁 **Dataset**: Publicly available QSAR Fish Toxicity dataset (used for educational purposes).
- ⚙️ **Models Used**:
  - Linear Regression
  - Ridge Regression (with hyperparameter tuning)
  - Lasso Regression 
  - Decision Tree Regressor (with hyperparameter tuning)
  - Random Forest Regressor
  - Bagging Regressor
  - AdaBoost Regressor
  - SVR (Support Vector Regressor) (with hyperparameter tuning)

## 🧪 Evaluation Metrics

Each model was evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Visualizations: Actual vs. Predicted scatter plots and residual analysis

## 📂 File Structure

```
QSAR_LC50_Toxicity_Prediction.ipynb    <- Main project notebook
qsar_fish_toxicity.csv                 <- Dataset used
```

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/pooja-pragatika22/qsar-lc50-toxicity-prediction.git
   ```
2. Open the notebook using Jupyter or any compatible environment.
3. Run the cells in order to reproduce the results.

> **Note**: Make sure all required libraries (`pandas`, `scikit-learn`, `matplotlib`, etc.) are installed.

## 👩‍💻 Author

**Pooja Pragatika Satpathy**  
Final Year B.Tech Student | Machine Learning Enthusiast

---

Feel free to fork this repository or raise issues for suggestions or improvements!
