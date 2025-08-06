# Student Result Prediction 🚀

A **machine learning project** that predicts whether a student will *pass* or *fail* based on exam scores and demographic data. This project leverages **Logistic Regression, Decision Tree, Random Forest, and SVM classifiers** to deliver accurate and insightful predictions—empowering educators and students alike!

---

## 🌟 Features

- **Automated Data Preprocessing:** Handles categorical encoding and feature engineering.
- **Multiple ML Models:** Compares Logistic Regression, Decision Tree, Random Forest, and SVM.
- **Performance Metrics:** Evaluates models with accuracy, precision, recall, F1-score, R², AUC.
- **Visual Insights:** Confusion matrix visualization for best-performing model.
- **Real-Time Prediction:** Instantly predict pass/fail for new student data.

---

## 🔥 Keywords

`Student Performance`, `Pass/Fail Prediction`, `Machine Learning`, `Classification`, `Logistic Regression`, `Decision Tree`, `Random Forest`, `SVM`, `Education Analytics`, `Python`, `scikit-learn`, `Data Science`

---

## 🚀 Quick Start

### 1. Install Required Libraries

```bash
pip install pandas scikit-learn matplotlib seaborn
```

### 2. Run the Code

- Upload your `StudentsPerformance.csv` dataset.
- The script automatically:
  - Loads and preprocesses data
  - Engineers an `avg_score` feature
  - Creates a binary `pass/fail` target
  - Encodes categorical variables
  - Splits data into train/test
  - Trains & evaluates four ML models
  - Displays performance metrics and confusion matrix
  - Allows real-time student prediction

### 3. Example Real-Time Prediction

```python
sample_input = {
    'gender': 'female',
    'race/ethnicity': 'group B',
    'parental level of education': "bachelor's degree",
    'lunch': 'standard',
    'test preparation course': 'none',
    'math score': 5,
    'reading score': 6,
    'writing score': 5
}
# Predict with best model and see result!
```

---

## 📊 Model Evaluation

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **R² Score**
- **AUC Score**
- **Classification Report & Confusion Matrix**

---

## 💡 Use Cases

- **Educational Insights**: Identify students at risk and tailor interventions.
- **Academic Analytics**: Enhance institutional performance tracking.
- **Predictive Modelling**: Apply to similar datasets for custom educational analytics.

---

## 📁 Dataset

The model expects a CSV file (like `StudentsPerformance.csv`) with columns:
- `gender`
- `race/ethnicity`
- `parental level of education`
- `lunch`
- `test preparation course`
- `math score`
- `reading score`
- `writing score`

---

## 🤝 Contributions

Contributions & improvements are welcome! Open an issue or submit a pull request.

---

## 🏷️ License

MIT License

---

*Empower student success with predictive analytics!*
