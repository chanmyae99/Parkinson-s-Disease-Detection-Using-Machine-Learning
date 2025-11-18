# Parkinson’s Disease Classification Using Machine Learning

This project uses machine learning models to classify **Parkinson’s disease** based on biomedical voice measurements.  
It demonstrates my skills in **data preprocessing, model training, evaluation, and working with real-world health datasets** 

---

## Project Overview
I built an end-to-end ML workflow to predict whether a person has Parkinson’s disease using the UCI Parkinson’s dataset.  
The project compares two models:

- **Decision Tree Classifier**
- **Gradient Boosting**

Gradient Boosting achieved the best performance with high accuracy and stable predictions.

---

---

## Dataset Information

- Source: UCI ML Repository  
- 195 samples, 22 biomedical voice features  
- Target:  
  - **1** → Parkinson’s  
  - **0** → Healthy  

Features include jitter, shimmer, HNR, RPDE, DFA, and other frequency-based measurements commonly used in clinical voice analysis.

---

## 🔧 Machine Learning Workflow

### **1️⃣ Data Preprocessing**
- Load and clean dataset  
- Remove unnecessary columns  
- Feature scaling  
- Correlation analysis  
- Train-test split  

### **2️⃣ Model Training**
Models implemented using **scikit-learn**:
- Decision Tree  
- Random Forest (with tuned hyperparameters)

### **3️⃣ Evaluation**
Measured using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  
- ROC Curve & AUC  

Random Forest performed the best.

---

## Key Results

| Model | Performance | Notes |
|-------|-------------|-------|
| **Decision Tree** | Good | Baseline model |
| **Gradient Boosting** | **92.1% accuracy** | Best model, stable and reliable |

---

## Visualizations Included

- Heatmap of feature correlation  
- Decision Tree diagram  
- Feature importance bar chart  
- Confusion matrix  
- ROC curve  

---



