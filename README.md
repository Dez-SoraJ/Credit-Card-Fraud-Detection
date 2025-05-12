# Credit-Card-Fraud-Detection
This project applies machine learning techniques to detect fraudulent credit card transactions. The dataset used is highly imbalanced, reflecting the real-world scenario where frauds are rare compared to legitimate transactions.

**Project Structure**
Credit_Card_Fraud_Detection.ipynb =  Main Jupyter notebook containing data preprocessing, exploratory data analysis (EDA), model training, evaluation, and conclusions.

**Dataset**
The dataset is derived from anonymized credit card transactions and contains the following:
284,807 transactions
492 fraud cases
Features: PCA-transformed values (V1 to V28), along with Time, Amount, and Class (target label)
Class Distribution:
0 → Non-Fraudulent
1 → Fraudulent

**Processes**

Handling class imbalance using techniques such as undersampling or oversampling

Feature scaling for numerical features

Visualizing class distribution

Correlation analysis

Machine Learning Models:

Logistic Regression

Decision Tree

Random Forest

XGBoost

**Evaluation Metrics**
Due to the class imbalance, accuracy alone is not a reliable metric. The models are evaluated using:

Confusion Matrix

Precision, Recall, F1-Score

ROC-AUC Curve

**How to Run**
1, Clone this repository or download the notebook.

2, Install dependencies (e.g., pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost if used).

3, Run the notebook cell by cell using Jupyter or any compatible environment.

4, Save the notebook in any of your pre-existing drives along with the dataset
