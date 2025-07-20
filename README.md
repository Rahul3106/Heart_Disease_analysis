# 🫀 Heart Disease Analysis & Prediction

This project explores the relationships among various cardiovascular health indicators and applies machine learning models to predict the presence of heart disease. The project includes visualizations, statistical insights, and classification models such as Logistic Regression, Decision Tree, and Random Forest—with performance improvements using SMOTE and ADASYN techniques.

## 🧪 Technologies Used

* **Python 3.8+**
* **Pandas, NumPy** – Data manipulation
* **Seaborn, Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning models
* **Imbalanced-learn** – SMOTE, ADASYN for data resampling
* **Jupyter Notebook** or similar environment

---

## 🧠 Project Highlights

* **Exploratory Data Analysis (EDA):**

  * Statistical distribution of features like age, cholesterol, max heart rate.
  * Gender-specific trends in heart disease.
  * Correlation heatmap for feature selection.

* **Supervised Learning Models:**

  * Logistic Regression for linear classification.
  * Decision Tree for interpretable, rule-based modeling.
  * Random Forest for robust ensemble predictions.

* **Model Evaluation:**

  * Confusion matrix, classification reports.
  * ROC-AUC analysis for Random Forest.

* **Class Imbalance Handling:**

  * Implemented **SMOTE** and **ADASYN** to address imbalanced heart disease classes.
  * Improved accuracy and recall on minority class.

---

## 📂 Files and Structure

```bash
📁 heart_disease_analysis/
│
├── 📜 Heart_Disease_analysis.ipynb     # Main notebook with analysis and models
├── 📜 README.md                        # Project overview
├── 📜 heart.csv                        # Dataset
                      
```
---

## 📈 Results

* Random Forest with SMOTE/ADASYN outperformed other models.
* ROC-AUC achieved: **0.81** on Random Forest.
* Insights revealed key risk factors: **Age**, **Sex**, **Max Heart Rate**, **Exercise-Induced Angina**, and **Cholesterol** levels.

---

## 📌 Future Improvements

* Include cross-validation for model robustness.
* Explore additional models (e.g., XGBoost, SVM).
* Deploy model using a Flask or Streamlit app for real-time predictions.

---

## 👨‍⚕️ Sample Use Case

Predict whether a patient with given clinical parameters (age, sex, cholesterol, max heart rate, etc.) is likely to have heart disease using trained models.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, raise issues, or submit pull requests.

