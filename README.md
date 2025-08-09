# 🌲 Covertype Classification Project 🌲  

This project focuses on classifying **forest cover types** using the UCI Covertype dataset.  
It compares **🌳 Random Forest** and **⚡ XGBoost** classifiers, including **hyperparameter tuning** for both models.  

---

## 📂 Dataset  
- **Source**: [UCI Machine Learning Repository – ID 31](https://archive.ics.uci.edu/ml/datasets/covertype)  
- **Features**: 54 attributes (elevation, soil type, wilderness area, etc.)  
- **Target**: Forest cover type (7 classes 🌲🌳🌵)  

---

## ⚙️ Requirements  
- **Python** 3.x
- **Required Packages**:
  - 🐼 pandas  
  - 📊 matplotlib  
  - 🤖 scikit-learn  
  - ⚡ xgboost  
  - 📦 ucimlrepo  
  - 🔢 numpy
  
- Install dependencies:  
```bash
pip install pandas matplotlib scikit-learn xgboost ucimlrepo numpy
```

## 🛠 Code Structure
- **1️⃣ Data Preparation**
  - 📥 Fetch dataset from UCI repository
  - ✂️ Split into train/test sets (80/20)
  - 📏 Apply StandardScaler for feature scaling

- **2️⃣ Random Forest Classifier 🌳**
  - 🔹 Baseline model with default parameters
  - 🎯 Hyperparameter tuning via GridSearchCV
  - 📈 Evaluation:
    - ✅ Accuracy score
    - 📊 Confusion matrix
    - 🌟 Feature importance visualization

- **3️⃣ XGBoost Classifier ⚡**
  - 🔹 Baseline model with default parameters
  - 🎯 Hyperparameter tuning via RandomizedSearchCV
  - 📈 Evaluation:
    - ✅ Accuracy score
    - 📊 Confusion matrix
    - 🌟 Feature importance visualization
