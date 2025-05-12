# Credit-Card-Fraud-Detection
For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

In the banking industry, credit card fraud detection using machine learning is not only a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees as well as denials of legitimate transactions.

In this project we will detect fraudulent credit card transactions with the help of Machine learning models.
We will analyse customer-level data that has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group. 

## Table of Contents
1. [Importing dependencies](#p1)
2. [Exploratory data analysis](#p2)
3. [Splitting the data into train & test data](#p3)
4. [Model Building](#p4)
   * [Perform cross validation with RepeatedKFold](#p4-1)
   * [Perform cross validation with StratifiedKFold](#p4-2)
   * [RandomOverSampler with StratifiedKFold Cross Validation](#p4-3)
   * [Oversampling with SMOTE Oversampling](#p4-4)
   * [Oversampling with ADASYN Oversampling](#p4-5)
5. [Hyperparameter Tuning](#p5)
6. [Conclusion](#p6)

   
