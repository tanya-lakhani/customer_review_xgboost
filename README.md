# Customer Review Prediction using XGBoost  

This project develops a machine learning model to predict customer review sentiment. After benchmarking multiple classifiers, **XGBoost** was selected for its strong performance on imbalanced data, enabling more reliable targeting of positive reviews.  

---

## 🚀 Features  
- Compared multiple models: Logistic Regression, Random Forest, Decision Tree, and XGBoost.  
- Applied **SMOTE** for balancing minority/majority classes.  
- Designed a **custom weighted metric** (70% Recall, 30% Precision) to prioritize capturing positive reviews.  
- Tuned hyperparameters with **RandomizedSearchCV** for optimal performance.  
- Evaluated using Accuracy, Precision, Recall, F1 (micro/macro), and confusion matrices.  

---

## ⚙️ Tech Stack  
- Python (Scikit-learn, imbalanced-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn)  

---

## 📊 Results  
- **XGBoost** achieved the best trade-off between recall and precision compared to baseline models.  
- Weighted scoring ensured majority of positive reviews were captured while maintaining acceptable overall accuracy.  
- Confusion matrix visualizations showed balanced performance across training and testing sets.  

---

## 👩‍💻 Author  
**Tanya Lakhani**  
MSc Business Analytics, Warwick Business School  

---

## 📌 How to Run  
1. Clone the repo:  
   ```bash
   git clone https://github.com/tanya-lakhani/customer-review-xgboost.git
   cd customer-review-xgboost
