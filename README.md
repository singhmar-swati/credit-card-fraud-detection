# credit-card-fraud-detection

**Overview:**
This project implements a neural network model to detect fraudulent credit card transactions. The model is trained and evaluated using Keras and Scikit-learn, leveraging cross-validation to ensure robust performance. The dataset used is the popular credit card fraud dataset, which contains transactions labeled as fraudulent or legitimate.

**Features:**
1. Data Standardization: Features are standardized to have zero mean and unit variance.
2. Class Imbalance Handling: Class weights are computed to address the imbalance between fraudulent and legitimate transactions.
3. Model Architecture: A simple neural network with SReLU activation and dropout for regularization.
4. Cross-Validation: Stratified K-Folds cross-validation to ensure consistent performance across different data splits.
5. Performance Evaluation: Classification report, ROC curve, and Precision-Recall curve to evaluate model performance.
**Dependencies:**
Python 3.x
NumPy
Pandas
Matplotlib
Seaborn
Keras
Keras-Contrib
Scikit-learn
