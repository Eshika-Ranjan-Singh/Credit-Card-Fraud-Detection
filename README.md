# Credit-Card-Fraud-Detection
# 💳 Credit Card Fraud Detection using Machine Learning

This project explores how machine learning algorithms can be used to detect fraudulent credit card transactions. Using an imbalanced real-world dataset, we apply multiple classification models and techniques to improve accuracy and reliability in fraud detection — a domain where even small errors can have significant consequences.

## 📂 Dataset

The dataset used in this project is available on [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)\cite{kaggle_fraud_data}. It contains transactions made by European cardholders over a two-day period in September 2013. Out of 284,807 transactions, only 492 are labeled as fraudulent — making the data highly imbalanced.

## 🧠 Models Used

The following machine learning models were trained and evaluated:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**

These models were selected for their balance between interpretability and performance in binary classification tasks.

## ⚙️ Techniques Applied

- **Data Preprocessing:** Normalization and feature separation.
- **Class Imbalance Handling:** SMOTE (Synthetic Minority Over-Sampling Technique) was used to oversample the minority class (fraudulent transactions).
- **Train-Test Split:** 80% for training, 20% for testing.
- **Class Weighting:** Applied to improve detection of the minority class.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC-AUC, and Precision-Recall curve.

## 📊 Results Summary

- **Random Forest** showed the most reliable performance overall, achieving high precision and recall with low false positive/negative rates.
- **Logistic Regression** achieved the highest ROC-AUC score (0.99), showing strong discriminatory power.
- **Decision Tree** offered simplicity but underperformed compared to ensemble methods.

## 📈 Visuals

The notebook includes visualizations of:
- Class distribution (before and after SMOTE)
- Confusion matrices
- ROC and Precision-Recall curves for each model

## 🔍 Key Takeaways

- Handling class imbalance is crucial for fraud detection.
- Ensemble models like Random Forest strike a good balance between accuracy and stability.
- Simple models like Logistic Regression can perform surprisingly well with proper preprocessing.

## 🛠️ Future Work

- Explore deep learning approaches (e.g., LSTM for transaction sequences)
- Evaluate performance in real-time environments
- Experiment with additional feature engineering or domain-specific datasets

## 🧾 Citation

If you're using this repository or dataset for research or educational purposes, please cite the original dataset:

> Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015.

## 📌 Disclaimer

This project is for educational and research purposes only. Real-world deployment of fraud detection systems requires continuous updates, ethical considerations, and compliance with data protection regulations.

---


