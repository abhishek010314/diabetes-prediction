# diabetes-prediction
Diabetes prediction using data analysis &amp; ML on health metrics — includes cleaning, visualization, feature engineering, and model evaluation.

This repository contains a complete end-to-end data analysis and machine learning project for predicting the likelihood of diabetes using the Pima Indians Diabetes dataset.

## 📊 Dataset Description
The dataset consists of medical diagnostic measurements for Pima Indian women. It includes 768 rows and 9 columns (8 features + 1 target).

### Features:
- **Pregnancies**
- **Glucose**
- **BloodPressure**
- **SkinThickness**
- **Insulin**
- **BMI**
- **DiabetesPedigreeFunction**
- **Age**
- **Outcome** (0 = Non-diabetic, 1 = Diabetic)

## 📌 Project Steps
1. **Data Loading & Cleaning**
   - Replaced invalid zeros in Glucose, BloodPressure, SkinThickness, Insulin, and BMI with NaN.
   - Imputed missing values using median strategy.

2. **Exploratory Data Analysis (EDA)**
   - Boxplots revealed outliers in Insulin, BMI, SkinThickness, and Age.
   - Correlation heatmap showed Glucose had the strongest correlation with diabetes outcome.

3. **Feature Scaling & Splitting**
   - Applied `StandardScaler` for normalization.
   - Split dataset into train and test sets (80-20).

4. **Model Building & Evaluation**
   - Trained Logistic Regression, KNN, and Random Forest.
   - **Random Forest** performed best with ~78% accuracy.
   - Evaluation metrics included confusion matrix and classification report.

5. **Feature Importance**
   - Top predictors: Glucose, BMI, DiabetesPedigreeFunction, and Age.

## ✅ Conclusion
This project provides a solid baseline for diabetes prediction using traditional machine learning models. Further improvement can be done via hyperparameter tuning or advanced algorithms.

## 📁 Files
- `diabetes_prediction.ipynb` – Jupyter Notebook with full workflow.
- `README.md` – Project overview and documentation.

---

### 🔗 Author
Built with ❤️ by a Data Analyst enthusiast.
