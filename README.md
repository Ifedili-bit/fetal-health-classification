# fetal-health-classification
Deep learning model to classify fetal health (Normal, Suspect, Pathological) using Cardiotocography (CTG) data.
## 📌 Project Overview
Cardiotocography (CTG) is a cost-effective and non-invasive method to monitor fetal heart rate and uterine contractions.  
In this project, I trained a neural network model to classify fetal health into three categories:
- **Normal**
- **Suspect**
- **Pathological**

---

## 📊 Dataset
- **Source:** [UCI Machine Learning Repository – Fetal Health](https://archive.ics.uci.edu/ml/datasets/Fetal+Health)  
- **Samples:** 2,126 records  
- **Features:** 21 extracted features from CTG exams  
- **Target Classes:**
  - 1 → Normal  
  - 2 → Suspect  
  - 3 → Pathological  

Class Distribution:  
- Normal → ~78%  
- Suspect → ~14%  
- Pathological → ~8%  

---

## 🧠 Model
- **Type:** Deep Neural Network (DNN)  
- **Layers:** Dense layers with ReLU activations + Dropout for regularization  
- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC AUC, PR AUC  

---

## 📈 Results
On the test set:  
- **Accuracy:** ~90.3%  
- **Macro Precision:** 0.84  
- **Macro Recall:** 0.86  
- **Macro F1 Score:** 0.85  
- **ROC AUC:** 0.97  
Confusion Matrix:
[[459 36 2]
[ 13 73 2]
[ 5 4 44]]
Confusion Matrix: 
