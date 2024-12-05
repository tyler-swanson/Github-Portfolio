# Home Credit Default Risk Assignment
This portfolio showcases my individual data science work, developed through my Master of Business Analytics coursework and hosted on GitHub. It highlights my proficiency in data analysis, visualization, and reproducible workflows, with an emphasis on delivering actionable business insights and practical solutions.

## Business Problem:
People often have a difficult time when it comes to getting loans due to a lack of credit history. This
can lead to financial challenges and even result in loans being placed with unethical lenders. Home
Credit Group is looking to solve this issue by providing a positive and safe borrowing experience to
people that lack traditional credit history. One of Home Credit’s challenges is unlocking the full
potential of their data to ensure their current system for predicting who can repay loans is accurate.
Currently, some customers that should qualify for a loan are being wrongly rejected due to
limitations in Home Credit Group’s system.

### Benefit of a solution:
If Home Credit Group can enhance their prediction system to more accurately assess a customer’s
ability to repay loans, they will be able to offer ethical lending options to those in need. Unlocking
the full potential of their data will also ensure that the loan terms and conditions they provide will
empower their clients to be successful.

### Success Metrics:
1. Increase the rate of approved loans for customers that can repay. The more qualified clients
that work with Home Credit, the fewer loans that will be placed with unethical lenders.
2. Decrease loan default rates.
3. Provide clients with loan terms and conditions that will empower their success.

### Analytics Approach:
Use a supervised machine learning methods to improve Home Credit Group’s predictive power
when determining the binary target variable of repayment ability. Since the goal is to determine if a
client will be able to repay their loan or not, this is a classification problem of yes or no.

### Scope:
To goal of this project is to create a better model to predict if a client will be able to repay their loan
and to provide better information on loan terms that will empower their client’s success.
### Details:
This project will be completed by an individual MABA student over the 2024 Fall Semester. The
project will be finished before January 2025. Important milestones will be Data Understanding,
Data Preparation, Modeling, Evaluation, and Deployment. 

## [EDA](https://github.com/tyler-swanson/EDA-2/blob/main/EDA%202.Rmd)
This project focuses on improving Home Credit Group's system for predicting loan repayment by using data analysis and machine learning. The aim is to reduce the rejection of qualified customers and promote ethical lending practices. By conducting exploratory data analysis, we’ll identify important patterns and insights to guide the development of a more accurate prediction model

*Target Variable:* TARGET - target variable (1 - client with payment difficulties: he/she had late payment more than X days on at least one of the first Y installments of the loan in our sample, 0 - all other cases)

![](https://github.com/tyler-swanson/Github-Portfolio/blob/main/Target%20Variable%20Distribution.png)

*Guiding Questions:* 1. What is the distribution of the target variable? 2. Which numerical variables have the strongest correlations with the target variable? 3. How do categorical variables relate to the target variable? 4. How much missing data is present, and is there a pattern to it? 5. Are there any significant outliers or anomalies in the data? 6. How does repayment behavior change over time? 7. Which groups of clients are most likely to default? 8. How do external data sources impact repayment predictions? 9. Which features are most important for predicting the target variable?

![](https://github.com/tyler-swanson/Github-Portfolio/blob/main/Top%20Predictors%20.jpg)

![](https://github.com/tyler-swanson/Github-Portfolio/blob/main/Screenshot%202024-12-04%20183154.jpg)

## [Model Exploration ](https://github.com/tyler-swanson/EDA-2/blob/main/Modeling.Rmd)
This project explores predictive modeling using two datasets, application_train and application_test. Through feature engineering, new variables ratios are created to enhance model performance. The analysis includes training and evaluating multiple models, including as Logistic Regression, Random Forest, and XGBoost, with ROC-AUC used as the primary evaluation metric. The workflow involves ensuring feature consistency between datasets, fine-tuning models, and analyzing their performance. The exploration concludesusing the best-performing model to make predictions and creating a submission file to receive a Kaggle score.  




# Home Credit Submission Criteria
### Business Problem and Project Objective
Home Credit Group faces financial challenges due to loan defaults and struggles to accurately predict who is likely to default. The imbalance in the dataset makes it hard to build models that can correctly identify defaulters without rejecting too many eligible applicants. This creates inefficiencies and limits Home Credit's ability to offer loans to people who lack traditional credit history.

The objective of this project is to create a better predictive model to improve the identification of potential defaulters while minimizing false rejections. Using methods like upsampling, ensemble modeling, and feature engineering, my goal was to improve accuracy and provide actionable insights.

### Business Problem Solution
The solution involves building a supervised machine learning model to enhance Home Credit Group's ability to predict loan repayment outcomes. By leveraging advanced analytics techniques, the project will improve the accuracy of the current prediction system and mitigate issues caused by imbalanced datasets.

### Personal Contribution
I contributed to this project by cleaning the dataset, addressing missing values, outliers, and inconsistencies, and analyzing patterns in the data. I engineered features to boost model performance and applied machine learning models, including logistic regression and random forests, optimizing them through grid search.To handle class imbalance, I used upsampling and cost-sensitive algorithms to improve predictions for minority classes. I evaluated models using precision, recall, and F1-scores, ensuring balanced results.

### Business Value of the Solution
The solution helps Home Credit better identify reliable borrowers, reducing defaults while increasing loan approvals for underserved clients. This improves customer satisfaction, expands revenue, and minimizes financial risks. Additionally, it refines loan terms to support borrower success and strengthen Home Credit's reputation.

### Difficulties Encountered
The main difficulty was addressing the large class imbalance in the dataset. Defaulters were significantly outnumbered by non-defaulters. This made it difficult to train models that accurately identified defaulters without misclassifying too many reliable borrowers. We used upsampling carefully selected evaluation metrics to overcoming this issue.

### Project Learnings
During this project, I learned how to address real-world data challenges like missing values, outliers, and class imbalance while building predictive models. I gained experience with feature engineering, applying machine learning models like logistic regression and gradient boosting, and tuning hyperparameters to optimize performance.



