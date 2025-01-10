# Credit-Card-Fraud-Detection

Data source : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download

This project focuses on detecting fraudulent credit card transactions using anomaly detection techniques. The dataset contains highly imbalanced data with numerical features derived from PCA transformation. Three models were evaluated: Isolation Forest, Local Outlier Factor (LOF), and One-Class SVM.

Key highlights:

Isolation Forest outperformed other methods, achieving 99.74% accuracy in fraud detection.
LOF and SVM showed lower precision and recall, with SVM being significantly less effective.
Techniques like under-sampling and SMOTE were used to address class imbalance.
