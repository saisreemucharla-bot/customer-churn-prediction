# Customer Churn Prediction

## 📌 Objective

The goal of this project is to predict whether a customer will churn (leave the service) using machine learning techniques and identify key factors that influence customer retention.

---

## 📊 Dataset

* Telco Customer Churn Dataset (Kaggle)
* ~7000 customer records
* Features include:

  * Contract type
  * Monthly charges
  * Tenure
  * Payment method
  * Internet services

---

## ⚙️ Approach

### Data Preprocessing

* Converted data types and handled missing values
* Removed irrelevant columns (customerID)
* Encoded categorical variables using one-hot encoding
* Scaled features using StandardScaler

### Model Building

* Logistic Regression model was used as baseline
* Model trained on 80% of data and tested on 20%

---

## 📈 Results

* Accuracy: **~79%**
* The model performs well in predicting non-churn customers
* Moderate performance in identifying churn customers

---

## 📊 Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## 🔍 Key Insights

* Customers with **month-to-month contracts** are more likely to churn
* Higher **monthly charges** increase churn probability
* Customers with longer tenure are less likely to leave
* The model misses some churners, indicating the need to improve recall

---

## 🧠 Model Evaluation

* Accuracy alone is not sufficient for churn prediction
* Recall for churn class is moderate (~51%)
* Reducing false negatives is important to minimize business loss

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 📂 Project Structure

* `notebooks/` → Jupyter notebook
* `images/` → visualizations
* `README.md` → project overview

---

## 🚀 Future Improvements

* Improve recall using class balancing
* Try advanced models (Random Forest, XGBoost)
* Perform hyperparameter tuning
* Deploy model using Streamlit

---

## 💼 Author

Saisree Mucharla
GitHub: https://github.com/saisreemucharla-bot
