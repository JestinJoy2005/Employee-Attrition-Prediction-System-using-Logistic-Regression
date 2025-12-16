Employee-Attrition-Prediction-System-using-Logistic-Regression
Employee Attrition Prediction System

Overview
Employee attrition is a major challenge for organizations. This project uses **Machine Learning (Logistic Regression)** to predict whether an employee is likely to leave or stay based on various workplace and personal attributes.

The model handles class imbalance using **Random Over Sampling** and provides an **interactive Gradio web interface** for easy prediction.

Features
- Data preprocessing and cleaning
- Label encoding and one-hot encoding
- Class imbalance handling using RandomOverSampler
- Logistic Regression model training
- Model evaluation using accuracy
- Interactive Gradio-based web application
- Real-time prediction with probability score

---
Machine Learning Algorithm
- **Logistic Regression**
- Oversampling Technique: **RandomOverSampler (imbalanced-learn)**

---

 Dataset
- CSV file uploaded by the user (e.g., HR Employee Attrition dataset)
- Target variable: `Attrition`
  - `0` → Likely to Stay  
  - `1` → Likely to Leave  

---

 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn
- Gradio
- Google Colab

---

Installation
Install required dependencies:

```bash
pip install gradio imbalanced-learn pandas numpy scikit-learn matplotlib seaborn

