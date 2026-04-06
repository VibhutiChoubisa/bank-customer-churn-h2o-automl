# bank-customer-churn-h2o-automl
📌 Project Overview

This project predicts whether a bank customer will exit (churn) or remain active using machine learning and deep learning techniques. It compares two approaches:

Artificial Neural Network (ANN) using TensorFlow/Keras
H2O AutoML for automated model selection and optimization

The goal is to identify customers at risk of leaving so that the bank can take preventive actions.

🎯 Problem Statement

Customer churn is a major issue in the banking sector. Retaining existing customers is more cost-effective than acquiring new ones. This project builds predictive models to classify whether a customer will exit based on their demographic and financial data.

📊 Dataset

The dataset contains bank customer information such as:

Credit Score
Geography
Gender
Age
Tenure
Balance
Number of Products
Credit Card status
Active Membership status
Estimated Salary
Target: Exited (0 = No, 1 = Yes)

| Model       | Accuracy         | Notes                             |
| ----------- | ---------------- | --------------------------------- |
| ANN (Keras) | ~85%             | Good baseline deep learning model |
| H2O AutoML  | Higher stability | Best ensemble model selected      |

