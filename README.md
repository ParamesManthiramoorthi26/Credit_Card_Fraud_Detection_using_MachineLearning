# Credit_Card_Fraud_Detection_using_MachineLearning
## Project Overview
With online transactions becoming more common, protecting credit card users from fraud is more important than ever. This project focuses on building a machine learning model that detects fraudulent transactions in real-time. By leveraging advanced algorithms, the goal is to minimize financial losses while keeping false alarms low.

## Understanding the Dataset
The dataset contains detailed transaction records, including:
* *Transaction Details* – Amount, date, time, location, and merchant category.
* *Cardholder Information* – Age, gender, monthly income, and spending habits.
* *Card & Device Info* – Card type, credit limit, and device used for the transaction.
* *Fraud Indicator* – Whether a transaction was fraudulent (Yes/No).

## How Well Did the Model Perform?
After testing various machine learning models, Random Forest provided the best results:
* *86% Accuracy* – The model correctly identified 86 out of every 100 transactions.
* *93% Precision* – When it flagged fraud, it was right 93% of the time, minimizing false alarms.
* *50% Recall* – It caught half of the actual fraud cases but still missed some.
* *F1-Score of 0.65* – A moderate balance between precision and recall.

# What We Learned
* *Preprocessing is Key* – Cleaning data, encoding labels, and using resampling techniques like upsampling helped improve accuracy.
* *Balancing the Data Matters* – Fraud cases were rare, so models like Logistic Regression, SVM, and Naïve Bayes struggled to detect them effectively.
* *Random Forest Stood Out* – It handled the imbalance better than other models.

## Challenges & Next Steps
* The biggest challenge? Fraud is rare, making it tricky to train a model that catches all cases without over-flagging normal transactions.

# What’s next?
* Use SMOTE (Synthetic Minority Over-sampling Technique) to generate more fraud cases and improve recall.
* Enhance features by incorporating behavioral patterns.
* Deploy the model in real-time with continuous learning for better adaptability.
