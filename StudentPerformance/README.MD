# Student Performance Prediction

This repository contains a Kaggle Notebook project that demonstrates a full end‑to‑end machine learning pipeline for predicting **Performance Index** using Nikhil’s Kaggle dataset:

**Dataset:** [https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)

**GitHub Repo URL:**
[https://github.com/sinahosseinzadeh97/Kaggle\_Project/tree/main/StudentPerformance](https://github.com/sinahosseinzadeh97/Kaggle_Project/tree/main/StudentPerformance)

---

## 📋 Project Structure

```
StudentPerformance/
├── data/
│   └── Student_Performance.csv      # Raw dataset
├── notebooks/
│   └── Student_Performance_Prediction.ipynb  # All analysis & code
├── images/
│   ├── Visualizing_RelationShip.png
│   ├── predicted(test).png
│   ├── Residual_analysis.png
│   ├── QQ_PLOT.png
│   └── Feature_Importance.png
├── requirements.txt                 # Python dependencies
└── README.md                        # You are here
```

---

## 🚀 Quick Start

1. **Clone the repo**:

   ```bash
   ```

git clone [https://github.com/sinahosseinzadeh97/Kaggle\_Project.git](https://github.com/sinahosseinzadeh97/Kaggle_Project.git)
cd Kaggle\_Project/StudentPerformance

````
2. **Install dependencies**:
   ```bash
pip install -r requirements.txt
````

3. **Launch Notebook**:

   ```bash
   ```

jupyter notebook notebooks/Student\_Performance\_Prediction.ipynb

```
4. **Run all cells** in order to reproduce data loading, EDA, feature engineering, modeling, and evaluation.

---

## 🔍 Tutorial Overview

1. **Data Loading & EDA**
   - Inspect types, null counts
   - Visualize distributions and correlations
2. **Preprocessing**
   - Encode `Extracurricular Activities` → `Extra_Activity_Binary`
   - Train/test split (80/20)
3. **Feature Engineering**
   - Log-transform skewed counts
   - Create interaction/ratio features
4. **Modeling**
   - Linear Regression
   - Ridge Regression (tuned via GridSearchCV)
   - Lasso Regression with cross-validation
5. **Evaluation**
   - Metrics: MSE, RMSE, R² (train/test & CV)
   - Visualization: Actual vs Predicted, Residuals, Q–Q plots
   - Coefficient & feature importance comparison
6. **Conclusion & Next Steps**
   - Summary of model performance
   - Recommendations for production use

---

## 📖 Notes

- No local data download needed—raw CSV is included in **data/**.  
- All plots and results are reproducible in Kaggle or locally once dependencies are installed.  
- Feel free to fork and extend: try other regressors, add more features, or deploy as a web app.

---

## 🤝 Contributing

Pull requests and issues are welcome! This repo is intended as a learning resource for beginners in machine learning.

---

## 📄 License

MIT License. See `LICENSE` in the root for details.

```
