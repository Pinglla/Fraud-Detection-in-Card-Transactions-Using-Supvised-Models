# Fraud-Detection-in-Card-Transactions-Using-Supvised-Models

## Project Overview

### Introduction
Fraudulent transactions pose a significant challenge in the financial sector, leading to financial losses, reputational damage, and customer distrust. This project aims to enhance fraud detection capabilities by leveraging supervised machine learning models to identify fraudulent transactions with high accuracy.

### Objective
The goal of this project is to build a robust fraud detection model that accurately classifies transactions as fraudulent or legitimate. By utilizing various machine learning techniques, we aim to improve detection rates, minimize false positives, and optimize financial savings for the business.

### Methodology
1. Data Acquisition & Preprocessing
   - The dataset consists of 97,852 credit card transactions from a U.S. government organization in 2010.
   - Data cleaning involved handling missing values, removing outliers, and addressing inconsistencies.

2. Feature Engineering & Selection
   - New variables were created based on transaction patterns, frequency, and geographical data.
   - Feature selection was conducted using various models, ensuring only the most predictive features were retained.

3. Model Development & Evaluation
   - Multiple machine learning models were tested, including Logistic Regression, Decision Trees, Random Forest, LightGBM, CatBoost, XGBoost, and Neural Networks.
   - Model performance was evaluated using metrics such as Fraud Detection Rate (FDR), precision, recall, and financial impact.
   - The final model, a Neural Network (Multi-Layer Perceptron), demonstrated the highest fraud detection efficiency with minimal overfitting.

4. Financial Optimization
   - A cost-benefit analysis was conducted to determine the optimal fraud detection threshold.
   - A recommended cutoff of 5% was identified to balance fraud detection effectiveness and financial savings.

### Key Findings
- Geographic transaction patterns (state and zip code) were significant indicators of fraud.
- The Neural Network model outperformed other models in detecting fraudulent activities with a high FDR.
- Implementing the recommended model and cutoff strategy can significantly reduce fraud-related losses while minimizing false positives.

### Conclusion & Future Work
This project successfully developed a machine learning-based fraud detection system capable of identifying fraudulent transactions with high precision. Future improvements may include hyperparameter tuning via automated techniques, integration with real-time fraud detection systems, and incorporating additional transaction attributes for improved model accuracy.

By leveraging advanced analytics and machine learning, organizations can enhance their fraud prevention strategies and mitigate financial risks effectively.


P.S The foundational code for this project was provided by the professor, and my primary task involved refining the code and adapting it to achieve the desired outputs.
