# Heart Disease Prediction Project

This project uses Machine Learning to predict whether a patient is at risk of a heart attack based on clinical medical data. The model analyzes various physiological factors and cardiac biomarkers to provide a binary classification (Heart Attack: Yes/No).

## 🩺 Dataset Features
The dataset consists of 1,319 records with the following attributes:
* **Age**: Patient's age.
* **Gender**: Biological sex (1 = Male, 0 = Female).
* **Heart Rate**: Beats per minute.
* **Systolic/Diastolic BP**: Blood pressure readings.
* **Blood Sugar**: Glucose levels.
* **CK-MB**: Cardiac enzyme indicating heart muscle damage.
* **Troponin**: Protein biomarker for heart injury.
* **Result**: Target label (1 = Positive, 0 = Negative).

## 🚀 Project Workflow
1. **Problem Definition**: Predict heart disease presence with high accuracy.
2. **Data Analysis**: Exploring distributions, checking for missing values, and identifying outliers.
3. **Modeling**: Comparing multiple classifiers:
   * Logistic Regression
   * K-Nearest Neighbors (KNN)
   * Random Forest Classifier
4. **Hyperparameter Tuning**: Optimization using `RandomizedSearchCV` and `GridSearchCV`.

## 🛠️ Requirements
To run this notebook, you will need:
* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

## 📈 Performance Target
The initial goal for this project is to achieve an evaluation accuracy of **95%**.
