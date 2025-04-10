# Fake_Account_Detection_Using_Machine_Learning
A machine learning project to detect fake social media accounts using profile data. Combines classification models with cybersecurity principles to identify malicious or deceptive users. Helps enhance digital safety through automated threat detection.

---

## 🎯 Objectives

- Apply machine learning techniques for classification
- Detect fake accounts based on profile-based features
- Evaluate model performance using ROC and AUC
- Show how ML can support cybersecurity by automating threat detection

---

## 🛡️ Relevance to Cybersecurity

Fake accounts are often used in:
- Phishing attacks
- Misinformation campaigns
- Social engineering
- Bot-driven fraud

This project aims to build a baseline ML model that can aid in the **automated detection** of such accounts, acting as a **first layer of defense** in social media cybersecurity workflows.

---

## 📊 Dataset Overview

Features include:
- Username and full name structure
- Bio/description length
- Number of posts, followers, following
- Profile image and verification status

**Target Variable**: `fake`  
- `0`: Real account  
- `1`: Fake account

---

## ⚙️ Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📉 ML Models Used

- Logistic Regression
- Regularized Logistic Regression

Evaluated using:
- Accuracy
- Precision & Recall
- ROC Curve
- AUC Score

---

## 📈 Visualizations

- Pie charts for class balance
- Heatmap of feature correlations
- Pairplots
- ROC curves for model comparison

---

## 🧠 Key Findings

- Features like follower/following ratio, bio presence, and verification are strong predictors.
- Regularization helps improve generalization and reduce overfitting.
- Even basic models can significantly aid cybersecurity workflows.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Fake_Account_Detection_Using_Machine_Learning.git
   cd Fake_Account_Detection_Using_Machine_Learning
