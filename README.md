# Fraud Detection and Prevention in Financial Transactions

## 📊 Overview
This project focuses on improving fraud detection in financial transactions using machine learning models. The primary goal is to identify fraudulent transactions based on historical data and enhance the existing fraud detection system, reducing financial losses and improving customer trust. The models used in this project include **LightGBM**, **Random Forest**, and **XGBoost**, with a focus on performance metrics such as accuracy, sensitivity, and PPV.

## 🎯 Objectives
- **Fraud Detection**: Detect fraudulent transactions based on patterns in transaction amount, location, time, and customer behavior.
- **Model Evaluation**: Compare the performance of different machine learning models (LightGBM, Random Forest, XGBoost) to find the most effective for fraud detection.
- **Provide Solutions**: Propose solutions to improve the fraud detection system, particularly for customers aged 65 and above.

## 🧑‍💻 Data Sources
- **Synthetic Transaction Records**: 500,000 records of transaction data generated from fraud detection systems, including variables such as transaction amount, type, location, balance, and time.
- **Customer Demographics**: Age, location, transaction history, and customer activity.

## 🔧 Tools & Techniques
- **Machine Learning Models**: LightGBM, Random Forest, XGBoost, Logistic Regression.
- **Evaluation Metrics**: Accuracy, Sensitivity, Specificity, and Positive Predictive Value (PPV).
- **Confusion Matrix**: Used to analyze True Positives, False Positives, True Negatives, and False Negatives in fraud detection.

## 🔍 Key Findings
- **Fraud Patterns**: Fraudulent transactions are typically small and occur during periods of low customer activity, especially between **12 AM - 6 AM**.
- **Model Performance**: 
  - **LightGBM** achieved the highest accuracy (0.784) and AUC (0.871).
  - **Random Forest** and **XGBoost** performed comparably with slightly lower accuracy.

## 💡 Recommendations
- **Transaction Alerts**: Implement OTP verification and limit banking services for customers aged 65 and above during high-risk hours (12 AM - 6 AM).
- **Flagging Strategy**: Rather than blocking transactions immediately, flag suspicious accounts for further investigation to reduce false positives.
- **Regular Updates**: Send fraud pattern updates and summary statements, particularly on Wednesdays, to help customers identify potential fraud.

## 📈 Fraudulent Transactions Breakdown
- **57.32%** of fraudulent transactions were **online**.
- **32.92%** were **offline withdrawals**.
- **13.33%** were categorized as **others**.

## 🔗 References
- Sohony, I., Pratap, R., & Nambiar, U. (2018). *Ensemble learning for credit card fraud detection*. Proceedings of the ACM India Joint International Conference on Data Science and Management of Data, 289–294. https://doi.org/10.1145/3152494.3156815
- Fayzrakhmanov, R., Kulikov, A., & Repp, P. (n.d.). *The Difference between Precision-recall and ROC Curves for Evaluating the Performance of Credit Card Fraud Detection Models*. http://dx.doi.org/10.25673/5577

## ❗️Disclaimer
This project was developed as part of academic coursework and is shared here for educational and profolio purpose. Unauthorised use, reproduction or distribution is not permitted and may violate academic integrity policies. 
