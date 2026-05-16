# Customer_Transaction_Prediction
🧠 Project Overview
This project focuses on building a machine learning classification model to predict whether a bank customer will make a future transaction. The goal is to help the bank identify potential customers and improve targeting strategies.

🎯 Problem Statement
Develop a predictive model that can classify customers as likely or unlikely to perform future transactions based on historical data

🎯 Problem Statement
Task 1:-Prepare a complete data analysis report on the given data.
Task 2:-Create a predictive model which will help the bank to identify which customer will make transactions in future.


📁 Dataset Information
Dataset shape: 200,000 rows × 202 features
Target variable: Binary classification
0 → No transaction
1 → Will perform transaction
The dataset is highly imbalanced.

⚙️ Workflow
1. Data Preprocessing
Handling missing values
Feature scaling 
Train-test split
2. Handling Imbalance
Applied SMOTE (Synthetic Minority Oversampling Technique)
Balanced the training dataset to improve minority class learning
3. Models Used
Decision Tree Classifier
Logistic Regression
Random Forest Classifier

📊 Evaluation Metrics
Since this is a banking classification problem, emphasis is given to:
Accuracy
Precision
Recall 
F1-score

Model Performance Summary
| Model               | Accuracy | Recall (Class 1)    | F1-score |
| ------------------- | -------- | ------------------- | -------- |
| Decision Tree       | —        | —                   | —        |
| Logistic Regression | ⭐ Best   | **0.76**            | —        |
| Random Forest       | ~0.79    | Lower than Logistic | —        |


—
🏆 Final Model Selection
After evaluating all models, Logistic Regression was selected as the final model because:
It achieved the highest recall for the minority class
It performs better in imbalanced classification after SMOTE
It aligns with the business objective of identifying potential transacting customers


🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
Imbalanced-learn (SMOTE)
Matplotlib / Seaborn

🚀 Future Improvements
Try advanced boosting models (XGBoost / LightGBM)
Hyperparameter tuning for Logistic Regression
Threshold tuning to further improve recall
Feature selection to reduce dimensionality

👩‍💻 Author
Sukrutha C

📌 Conclusion
This project demonstrates a complete machine learning pipeline including data preprocessing, handling class imbalance, model building, evaluation, and final model selection based on business-oriented metrics.



