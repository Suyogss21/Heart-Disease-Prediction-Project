# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a person is suffering from heart disease using Machine Learning techniques. The goal is to build a reliable classification model that can assist in early diagnosis and healthcare decision-making.

---

## 📊 Dataset

* Source: Kaggle (Heart Disease UCI Dataset)
* Total Records: 303
* Features: 13 input features + 1 target variable
* Target:

  * `0` → No Heart Disease
  * `1` → Heart Disease Present

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

* Checked dataset structure using `.info()` and `.describe()` 
* No missing values found
* Visualized:

  * Correlation Matrix
  * Feature Distributions (Histograms)
  * Target Class Balance

---

## ⚙️ Data Preprocessing

* Converted categorical variables using **One-Hot Encoding**
* Applied **StandardScaler** for feature scaling
* Split dataset into:

  * Training set (67%)
  * Testing set (33%)

---

## 🤖 Machine Learning Models Used

### 1. K-Nearest Neighbors (KNN)

* Best Accuracy: **87%**
* Optimal K Value: **8 neighbors**

### 2. Support Vector Machine (SVM)

* Best Kernel: **Linear**
* Accuracy: **83%**

### 3. Decision Tree Classifier

* Accuracy: **79%**
* Tuned using different max features

### 4. Random Forest Classifier

* Best Accuracy: **84%**
* Optimal Estimators: **100 / 500**

---

## 📈 Model Comparison

| Model         | Accuracy     |
| ------------- | ------------ |
| KNN           | 87% ✅ (Best) |
| Random Forest | 84%          |
| SVM           | 83%          |
| Decision Tree | 79%          |

---

## 🧠 Key Insights

* Feature scaling significantly improved model performance
* KNN performed best among all models
* Dataset is balanced enough for reliable predictions
* Certain features show strong correlation with heart disease

---

## 💡 Business Impact

* Helps in early detection of heart disease
* Can assist healthcare professionals in decision-making
* Reduces risk by identifying high-risk patients early

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Use advanced models like XGBoost
* Deploy as a web app (Flask / Streamlit)
* Use larger real-world datasets

---

## 📌 Conclusion

This project demonstrates how Machine Learning can be effectively used in healthcare to predict heart disease. Among all models, **KNN achieved the highest accuracy of 87%**, making it the best-performing model for this dataset.

---

## 👨‍💻 Author

**Suyog Satane**
Aspiring Data Analyst / Data Scientist
