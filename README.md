# 💳 Credit Card Fraud Detection Using Machine Learning

This project builds a machine learning model to detect fraudulent credit card transactions using transaction patterns, user behavior, and other features. The model is trained using a real-world dataset and aims to improve fraud detection using data preprocessing, balancing techniques, and classification algorithms.

---

## 📁 Dataset

The dataset contains credit card transactions made in September 2013 by European cardholders. It includes features like:
- `Time`: Seconds elapsed between each transaction and the first transaction.
- `Amount`: Transaction amount.
- `V1` to `V28`: PCA-transformed features (for privacy).
- `Class`: Target variable (`0` for non-fraud, `1` for fraud).

---

## 🧠 Problem Statement

> Detect fraudulent transactions using classification models that learn from patterns in transaction data.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for ML algorithms)
- imbalanced-learn (for SMOTE)

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Load and explore dataset.
   - Drop unnecessary columns.
   - Scale features using `StandardScaler`.

2. **Handling Class Imbalance**
   - Use **SMOTE (Synthetic Minority Over-sampling Technique)** to generate synthetic fraud samples.

3. **Model Training**
   - Split dataset into training and test sets.
   - Train **Random Forest Classifier**.

4. **Model Evaluation**
   - Evaluate using **confusion matrix** and **classification report**.
   - Visualize performance and feature importance.

---

## 📊 Output

- **Accuracy:** High precision and recall for both fraud and non-fraud.
- **Confusion Matrix & Heatmap:** Clear visualization of prediction performance.
- **Feature Importance Plot:** Shows which features impact predictions most.

---

## 📸 Visuals

- Confusion Matrix Heatmap  
- Top 10 Feature Importances Barplot

---

## 📌 Results

The model performs well on imbalanced data, thanks to the use of SMOTE and Random Forest. The key metrics (precision, recall, F1-score) indicate that the model is effective at detecting fraud with minimal false positives and negatives.

---

## 📚 References

- [Kaggle Dataset: Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [SMOTE - Imbalanced Learn Docs](https://imbalanced-learn.org/)





