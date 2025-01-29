---

# **Diabetes Prediction Using Machine Learning**  

## **Overview**  
This project applies multiple machine learning algorithms to predict diabetes based on patient health data. The goal is to evaluate the performance of different models and identify the most effective one for accurate diabetes prediction.  

---

## **Dataset**  
The dataset used for this project is available on Kaggle: [Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).  
- **Description**: The dataset contains health-related attributes of individuals, which are used to predict the presence of diabetes.  
- **Target**: Binary classification (`1`: Diabetic, `0`: Non-Diabetic).  

---

## **Data Preprocessing**  
1. **Null and Duplicate Values**:  
   - Checked for missing or null values and handled them appropriately.  
   - Identified and removed duplicate entries to ensure data integrity.  

2. **Outlier Detection and Removal**:  
   - Used **Interquartile Range (IQR)** to detect and remove outliers, improving model performance and robustness.  

3. **Feature Scaling**:  
   - Standardized numerical features to ensure all attributes are on the same scale, aiding algorithms like SVC and Logistic Regression.  

4. **Train-Test Split**:  
   - Divided the dataset into **training** and **testing** subsets for unbiased model evaluation.  

---

## **Algorithms and Results**  
The following machine learning algorithms were implemented and evaluated:  

| **Algorithm**                 | **Accuracy (%)** |  
|--------------------------------|------------------|  
| Logistic Regression            | 75.79            |  
| Random Forest Classifier       | 85.26            |  
| Decision Tree Classifier       | 80.00            |  
| Support Vector Classifier (SVC)| 82.11            |  
| Gradient Boosting Classifier   | 86.32            |  

---

## **Project Workflow**  

1. **Data Preprocessing**:  
   - Handled null and duplicate values.  
   - Detected and removed outliers using the **IQR method**.  
   - Standardized features and split the dataset into training and testing sets.  

2. **Model Implementation**:  
   - Applied various machine learning models:  
     - Logistic Regression  
     - Random Forest Classifier  
     - Decision Tree Classifier  
     - Support Vector Classifier (SVC)  
     - Gradient Boosting Classifier (XGBoost)  

3. **Evaluation**:  
   - Used accuracy as the primary metric to compare model performance.  
   - Visualized the results to highlight the best-performing model.  

---

## **Setup and Usage**  

### **Prerequisites**  
Ensure you have the following installed:  
- Python 3.8+  
- Scikit-learn  
- XGBoost  
- Pandas  
- Matplotlib/Seaborn  


 View the evaluation results and predictions.  

---

## **Results Visualization**  
Visualization tools such as **Matplotlib** and **Seaborn** were used to:  
- Compare accuracy across different algorithms.  
- Highlight feature importance in tree-based models like Random Forest and Gradient Boosting.
- with gradient boosting algorithm the confusion matrix
  ![image](https://github.com/user-attachments/assets/da686b0a-2535-4d22-86cf-554f1d521f56)
 
---

## **References**  
- [Kaggle Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)  
- [Scikit-learn Documentation](https://scikit-learn.org/)  
- [XGBoost Documentation](https://xgboost.readthedocs.io/)  
