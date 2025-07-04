# QSAR-Based LC50 Toxicity Prediction | Machine Learning Bootcamp Project

This repository contains the final project notebook from a Machine Learning Bootcamp. The project focuses on implementing and comparing various supervised learning models to evaluate performance on a regression task involving LC50 (Lethal Concentration 50%) predictions using QSAR features.

🔗 **GitHub Repository**: [qsar-lc50-toxicity-prediction](https://github.com/pooja-pragatika22/qsar-lc50-toxicity-prediction)

## 📌 Project Highlights

- 📊 **Objective**: Predict LC50 values of chemicals using their QSAR (Quantitative Structure–Activity Relationship) descriptors.
- 📁 **Dataset**: Provided as part of the bootcamp (confidential and not publicly available).
- ⚙️ **Models Used**:
  - Linear Regression
  - Ridge Regression (with hyperparameter tuning)
  - Lasso Regression (with hyperparameter tuning)
  - Decision Tree Regressor
  - Random Forest Regressor
  - AdaBoost Regressor
  - SVR (Support Vector Regressor)

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
