## 🚀 Machine Learning Pipeline for Startup Success Prediction  

This repository contains a **machine learning pipeline** designed to predict the success or failure of startups based on various features. The dataset used comes from [Kaggle](https://www.kaggle.com/datasets/yanmaksi/big-startup-secsees-fail-dataset-from-crunchbase).  

### 📌 Project Overview  

The goal of this project is to evaluate multiple **machine learning models** and identify the best-performing one for predicting startup success. The pipeline includes:  

1. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling and encoding  
   - Data balancing (if needed)  

2. **Model Training & Evaluation**  
   - Testing multiple models:  
     - Logistic Regression  
     - Naive Bayes  
     - Support Vector Machine (SVM)  
     - K-Nearest Neighbors (KNN)  
     - Decision Tree  
     - Random Forest  
   - **Cross-validation** to ensure model stability  
   - Performance metrics: accuracy, confusion matrix, classification report  

3. **Hyperparameter Tuning**  
   - **Grid Search** applied to fine-tune the best model (Random Forest)  

4. **Final Model Assessment**  
   - Evaluating the best model on unseen test data  
   - **Feature Importance Analysis**  
   - **ROC Curve & AUC Score**  

### 🔍 Key Findings  

- **Random Forest** achieved the highest accuracy (**80.54%**) after hyperparameter tuning.  
- The **ROC-AUC score (0.84)** indicates strong predictive power.  
- The **most informative features** influencing the model were identified.  
- The model is **better at predicting failed startups** than successful ones, with high recall for failure cases.  

### 💊 Visualization  

- **Confusion Matrix** for performance evaluation  
- **ROC Curve** to measure classification ability  
- **Feature Importance Plot** to understand key drivers  

---  
