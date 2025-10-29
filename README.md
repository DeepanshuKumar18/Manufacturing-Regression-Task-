#  Manufacturing Data Analysis (Efficiency Prediction)

This project analyzes a **manufacturing dataset** containing details about departments, production processes, and work progress.  
The goal is to understand which factors most influence daily productivity and to build a model that can accurately estimate team efficiency based on operational data.

---

## Objectives
- Clean and preprocess manufacturing data.  
- Split dataset based on **WorkInProgress** null values.  
- Analyze production trends across departments.  
- Perform regression modeling to predict Efficiency.  
- Visualize department-wise insights and missing value patterns.

---

##  Key Steps
1. **Data Cleaning & Preparation**
2. **Data Splitting**
3. **Exploratory Data Analysis (EDA)**
4. **Model Building**
5. **Model Evaluation**
6. **Hyperparameter Tuning**

---

## Key Learnings

- Handled missing values in `workInProgress`, improving model accuracy.  
- Cleaned and standardized department names for consistent grouping.  
- Applied `StandardScaler` to normalize numerical data and enhance Linear Regression performance.  
- Compared multiple models — Linear Regression, Random Forest, and XGBoost — to identify the best fit.  
- Performed hyperparameter tuning using `GridSearchCV` for optimal model performance.  
- Visualized efficiency trends and feature importance to extract actionable insights.  
- Learned that ensemble models handle non-linear manufacturing data more effectively.  
- Understood how data-driven insights can help improve productivity and operational efficiency.  

##  Technologies Used
- Python   
- Pandas  
- NumPy  
- Matplotlib 
- Seaborn  
- Scikit-learn
- XGBoost
---

