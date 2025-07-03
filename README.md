# Employee Performance Analysis – INX Future Inc.

## Project Overview
This project focuses on analyzing employee data to identify the key factors influencing performance ratings. Using machine learning models, we predict performance categories and provide actionable insights to support HR in making data-driven decisions for improving workforce productivity and retention.

## Objective
To build a machine learning model that classifies employees based on their performance rating using historical employee data, and to derive insights that help enhance organizational HR strategies.

## Dataset
The dataset consists of various employee attributes including:
- Demographics (Age, Gender, Marital Status)
- Career History (Years at company, Years in current role, Job level)
- Compensation (Salary hike %, Overtime, Hourly rate)
- Performance-related data (Previous ratings, Promotions, Training)

## Key Steps
### 1. Exploratory Data Analysis (EDA)
- Identified patterns and distributions in employee attributes.
- Detected outliers and imbalance in the target variable.
- Visualized relationships between key features and performance ratings.

### 2. Data Preprocessing
- Handled missing values and outliers using statistical techniques.
- Encoded categorical variables using label encoding and manual mapping.
- Scaled continuous features for model consistency.
- Balanced the target variable using SMOTE to address class imbalance.

### 3. Feature Engineering
- Removed irrelevant features (e.g., Employee Number).
- Created meaningful features like years since last promotion and salary hike percentage.
- Analyzed feature correlations to avoid redundancy.

### 4. Model Building and Evaluation
Trained and evaluated multiple classification algorithms:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Bagging
- Gradient Boosting
- XGBoost
- AdaBoost
- Artificial Neural Networks (ANN)

**Best Model:**  
`XGBoost` delivered the highest performance with:
- **Accuracy:** 95%
- **F1-Score:** 95.00
- **Generalization:** Consistent training and testing accuracy

## Insights
- Employees with more experience and higher salary hikes tend to perform better.
- Lack of recent promotions or stagnant roles often lead to lower performance ratings.
- Departments like Sales and Finance show lower average ratings compared to HR and Development.
- Employees working overtime or commuting long distances tend to show lower performance.

## Recommendations
- Reassign long-tenured employees without promotion or role change.
- Increase training frequency, especially for low-performing departments.
- Offer better incentives and career growth for employees in the 2–4 rating range.
- Monitor overtime patterns and improve work-life balance policies.

## Conclusion
The model and analysis provide a foundation for HR decision-making to improve employee performance, engagement, and retention. XGBoost stands out as the most effective predictive model for this problem.

## Tools and Technologies Used
- Python, Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn, XGBoost, imbalanced-learn (SMOTE)
- Jupyter Notebook
