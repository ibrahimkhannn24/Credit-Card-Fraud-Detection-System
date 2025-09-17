# Credit Card Fraud Detection System
This project explores fraud detection using a real-world credit card transaction dataset. The dataset is highly imbalanced, with fraudulent transactions accounting for only 0.172% of all records. Key components of the project include:

- Data Preprocessing: Handled missing values, removed irrelevant outliers, and addressed class imbalance using under-sampling. Applied PCA for dimensionality reduction.
- Exploratory Analysis: Visualized the differences between fraudulent and non-fraudulent transactions, revealing key patterns in transaction amounts, time, and correlation structures.
- Modeling: Built and compared three classification models (LDA, SVM, KNN) using 5-fold cross-validation.
    - KNN: Best generalization with 86% test accuracy.
    - SVM: High training accuracy but signs of overfitting.
    - LDA: Performed moderately well with balanced results.
- Findings: Fraudulent transactions show higher variability in amounts and sporadic distribution over time, unlike the cyclical trends of non-fraudulent transactions.
  
This repository demonstrates end-to-end fraud detection, from preprocessing to model evaluation, using Python, Jupyter Notebook, and libraries like scikit-learn, matplotlib, and seaborn
