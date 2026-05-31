# 📞 Telecom Customer Churn Prediction using Machine Learning

This repository features an end-to-end Machine Learning project designed to predict customer churn in the telecommunications industry. Identifying potential churners allows businesses to take proactive retention measures before the customer leaves.

## 📊 Insights from Exploratory Data Analysis (EDA)
* **Contract Type:** Customers with **Month-to-month contracts** have an overwhelmingly higher churn rate compared to those on long-term (one or two-year) contracts.
* **Monthly Charges:** Higher monthly charges (especially above $70) strongly correlate with a higher probability of customer churn.

## 🛠️ Tech Stack & Processing
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib
* **Feature Engineering:** One-Hot Encoding for categorical features and `StandardScaler` for continuous numeric features.
* **Algorithm:** Random Forest Classifier

## 📈 Model Performance & Results
The Random Forest model achieved stable performance across both classes:

* **Overall Accuracy:** 68%
* **Churn Class Recall:** 0.56 (Successfully caught 56% of actual churners)
* **F1-Score:** 0.60

### Confusion Matrix Insights
The model successfully balances the trade-off between identifying churners (High Recall) and maintaining accuracy to prevent false loyalty offers.
