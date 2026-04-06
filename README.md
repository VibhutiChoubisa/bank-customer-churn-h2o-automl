# bank-customer-churn-h2o-automl
📌 Project Overview

This project predicts whether a bank customer will exit (churn) or remain active using machine learning and deep learning techniques. It compares two approaches:

-Artificial Neural Network (ANN) using TensorFlow/Keras
-H2O AutoML for automated model selection and optimization

<img width="797" height="503" alt="image" src="https://github.com/user-attachments/assets/3103b08d-a541-408c-b244-3afe731ac9d1" />

The goal is to identify customers at risk of leaving so that the bank can take preventive actions.

🎯 Problem Statement

Customer churn is a major issue in the banking sector. Retaining existing customers is more cost-effective than acquiring new ones. This project builds predictive models to classify whether a customer will exit based on their demographic and financial data.

📊 Dataset
<img width="1375" height="239" alt="image" src="https://github.com/user-attachments/assets/f5b5831a-fa4e-467d-8939-fc281d5c4263" />

3️⃣ ANN Model (Deep Learning)
Built using TensorFlow Sequential API
Architecture:
-Input layer - Hidden layers with activation functions (ReLU) - Output layer with Sigmoid activation
Training:
  - Epochs: 100
  - Optimizer: Adam
  - Loss: Binary Crossentropy
📈 ANN Results:
    - Training Accuracy: ~86%
    - Test Accuracy: ~85%
📊 Classification Report:
    - Precision (Churn): 0.76
    - Recall (Churn): 0.39
    - F1-score (Churn): 0.51

4️⃣ H2O AutoML Model
Used H2O AutoML to automatically train and compare multiple models.
Models included:
    - Gradient Boosting Machines (GBM)
    - Random Forest
    - Deep Learning
Stacked Ensembles
🏆 Best Model: 

<img width="874" height="292" alt="image" src="https://github.com/user-attachments/assets/7acfbd20-0b6c-46dd-ab30-dd674e300827" />


📊 Performance:
Confusion Matrix analysis shows improved balance between precision and recall
Best model selected using leaderboard ranking

| Model       | Accuracy         | Notes                             |
| ----------- | ---------------- | --------------------------------- |
| ANN (Tf)    | ~85%             | Good baseline deep learning model |
| H2O AutoML  | Higher stability | Best ensemble model selected      |

