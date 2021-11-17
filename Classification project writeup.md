# Employee Turnover Prediction 
## Aljowhara Alblaihed 

## Abstract
The goal of this project was to use classification models to predict whether an employee is going to leave or not leave the organization in
the coming period. worked with data provided by kaggle. I worked on some steps to help me how the companies and employees to increase employee
productivity, growth and a healthy environment in the company, and they steps are exploratory data analysis and data visualization after that 
built four models and includes Baseline, Logistic Regression, K-Nearest Neighbors and Random Forest.


## Design
The data is provided by kaggle. and have two class and they are Turnover and Not Turnover. Classifying statuses accurately via machine learning
models would enable the companies to take actions to improve company quality and productivity, maintain employees and company budget.


## Data
#### The dataset contains 14,999 employees and 10 Features. 

satisfaction_level: It’s the employee satisfaction rate, and values between 0-1.

last_evaluation: It’s evaluated performance by the employer, and values between 0-1.

number_projects: Number of projects completed while at work.

average_monthly_hours: Average monthly hours at workplace.

time_spend_company: Time spent at the company in years.

Work_accident: Whether the employee had a workplace accident, and values 0 or 1.

Left: Whether the employee left the workplace, and values 0 or 1.

promotion_last_5years: Whether the employee was promoted in the last five years.

Sales: Employee’s working department.

Salary: Salary level of the employee and have 3 levels low, medium and high.


## Algorithms
#### Feature Engineering
•	Rename columns for more readable.

•	Drop duplicated data.

•	Converting categorical features to binary dummy variables.


## Models
I used 4 models to predict the Employee Turnover rate and they are Baseline, Logistic regression, k-nearest neighbors, and random forest classifiers.
Random forest as the model with strongest performance. 

#### Model Evaluation and Selection
Split data into training and testing datasets. 70 train size and 30 test size.
Baseline model was very poorly performing and f1 score is 0.
The data is imbalance so I used f1 score as evaluation measure and F1 score is usually more useful than accuracy, especially if you have an uneven
class distribution and they are:

•	Baseline Model had a score of 0%.

•	Logistic Regression had a score of 25%.

•	K-Nearest Neighbors had a score of 84.5%.

•	Random Forest had a score of 93.9%.


## Tools
•	Numpy and Pandas for data manipulation.

•	Matplotlib and Seaborn for plotting.

•	Scikit-learn for modeling.


## Communication

### Target Distribution
![unnamed (2)](https://user-images.githubusercontent.com/75037992/142291073-732324b1-7b6a-4498-8663-c3eda4875d4e.jpg)

83.40% of employees stayed (not turnover) and 16.60% of employee left the company (turnover).
have an uneven class distribution.

### Correlation Between Features
![Correlation Between Features](https://user-images.githubusercontent.com/75037992/142292475-0315486f-5531-4eda-b355-8fa67129f945.jpg)

The most influential factor was employee satisfaction rate and  which had a score of 0.35.

### Compare Models
![unnamed (7)](https://user-images.githubusercontent.com/75037992/142291355-97e656d4-383c-499b-84ca-e6b097c42bc5.jpg)

Achieved the best result in Random Forest Classifier Model and had a score of 93.9%.

