# Edtech-retention-analysis

📌 Problem Statement

Online EdTech platforms face a major challenge:  
A significant number of students **drop out before completing their courses**.

This leads to:
- Loss of revenue for the platform
- Poor student success rates
- Inefficient use of marketing and onboarding efforts

❗ Key Problem:
> How can we identify students who are at risk of dropping out early and understand the factors affecting student retention?

🎯 Objective

The main goals of this project are:

- Analyze student behavior and engagement data
- Identify patterns that lead to student dropout
- Build a predictive model to classify students as:
  - Retained (will continue learning)
  - At-risk / Dropout
- Provide actionable insights to improve retention rates

💡 Proposed Solution

We solve this problem using a **Data Science + Machine Learning approach**:

Step 1: Data Analysis
Understand student behavior using:
- Engagement patterns
- Performance metrics
- Activity trends

Step 2: Feature Engineering
Create meaningful features such as:
- Average login frequency
- Course completion ratio
- Time spent on platform
- Assessment performance score

Step 3: Predictive Modeling
Train machine learning models to predict dropout risk:
- Logistic Regression
- Decision Tree
- Random Forest (best performing model)

Step 4: Insights Generation
Identify key drivers of dropout and retention.

📊 Dataset Description

The dataset contains student learning behavior data such as:

- Student ID  
- Login frequency  
- Time spent on platform  
- Number of courses enrolled  
- Course completion rate  
- Assignment scores  
- Participation activity  
- Dropout status (Target variable)

🛠️ Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn
- HTML
- CSS
- Jupyter Notebook  

🔍 Project Workflow

1. Data Collection
Collected student activity data from EdTech platform logs.

2. Data Cleaning
- Handled missing values  
- Removed duplicates  
- Encoded categorical variables  

3. Exploratory Data Analysis (EDA)
- Distribution of student activity  
- Dropout vs retained comparison  
- Correlation between features  

4. Feature Engineering
Created new features:
- Engagement score  
- Performance index  
- Activity level classification  

5. Model Building
Applied ML models:
- Logistic Regression  
- Decision Tree  
- Random Forest  

6. Model Evaluation
Evaluated using:
- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  

📈 Key Insights

- Students with **low login frequency** are more likely to drop out  
- **Course completion rate** is the strongest predictor of retention  
- Early inactivity is a strong warning sign of dropout  
- High engagement students have significantly higher success rates  
- Performance in assignments strongly correlates with retention  


📊 Visualizations

Include your graphs here:

- Student engagement distribution  
- Correlation heatmap  
- Dropout vs retained comparison  
- Feature importance chart

🤖 Model Performance (Classification Report)

The model was evaluated using a classification report on the test dataset.

          precision    recall  f1-score   support
  0           1.00      1.00      1.00     19614
  1           1.00      1.00      1.00     16123
  accuracy                        1.00     35737
  macro avg   1.00      1.00      1.00     35737

🚀 How to Run

pip install -r requirements.txt
python app.py



