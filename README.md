# Titanic Survival Analysis

### **Project Overview**
This project aims to predict the survival of passengers aboard the Titanic based on features such as Age, Gender, Class, and Ticket Fare. Using machine learning algorithms, the model identifies key factors contributing to survival and evaluates the predictive performance of various classification models.

---

### **Technologies Used**  
- **Python** (pandas, scikit-learn, matplotlib, seaborn)  
- **Jupyter Notebook** (for interactive analysis)  
- **Model Evaluation** (Confusion Matrix, AUC, Precision, Recall)  

---

### **Problem Statement**  
The Titanic dataset contains information about the passengers aboard the ill-fated ship, including demographics and whether they survived. The task is to build a machine learning model to predict whether a passenger survived or not based on their features. 

**Key Objectives:**
- Analyze the Titanic dataset and identify survival patterns.
- Engineer relevant features to improve model accuracy.
- Evaluate the predictive power of machine learning models.

---

### **Approach**  
1. **Exploratory Data Analysis (EDA)**  
   - Analyzed the dataset to understand distributions, relationships, and missing values.  
   - Visualized survival rates by Age, Gender, and Class using **matplotlib** and **seaborn**.

2. **Feature Engineering**  
   - Created new features such as **Family Size** (combining SibSp and Parch) and extracted **Cabin Info** from the full cabin number.  
   - Handled missing values (Age, Cabin) through imputation.

3. **Modeling**  
   - Built **Logistic Regression** and **Random Forest** models to predict survival outcomes.  
   - Evaluated models using **AUC**, **Confusion Matrix**, **Precision**, and **Recall**.  
   - Achieved **82% accuracy** with the best-performing models.

4. **Model Evaluation**  
   - Used **cross-validation** to validate the performance of each model.  
   - Selected the best model based on performance metrics.

---

### **Results**  
- **Best Model**: Random Forest  
- **Accuracy**: **82%**  
- **Key Predictors**: Gender (female passengers had higher survival rates), Class (First Class passengers had higher survival rates), Age (younger passengers had higher survival rates).
