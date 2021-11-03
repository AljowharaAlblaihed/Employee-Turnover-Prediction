# *Employee Turnover Prediction*

### *Introduction*
The Employee turnover analysis is important to the success of the company. A healthy work environment and high retention of good employees are the two most important
visions to the success of the company. A company experiences a high rate of employee turnover which can result in financial losses and wasted time in training new employees.
Understanding the factors that have been associated with employee turnover will allow companies and employees to increase employee productivity, growth and a healthy
environment in the company.

### *Business Problem*
The project is determine which factors/features have a high effect on employees turnover rate based on exploring data and create models that predict whether an employee
will leave the company or not.

### *Data*
I am working in this [dataset](https://www.kaggle.com/lnvardanyan/hr-analytics)
The data contains 14,999 employees observation with 10 features. The features contain the employee satisfaction rate, evaluated performance by the employer, number of 
projects for each employee, average number of hours worked per month, number of years spent by an employee in the company, whether an employee has had a work accident
or not, an employee had a promotion in the last 5 years or not, the employee has left the company or not, the department in which the employee works and salary level.

### *Algorithms*
*Feature Engineering*
•	Rename column names to more readable.
•	Not have null/missing values.
•	has 3,008 duplicate values.
•	Convert categorical data using get dummies.
•	Split data into training and testing datasets.

*Models*
The problem is predicting whether an employee is going to leave or not leave the company.
So, the data is classification.
I apply four models:
•	Baseline is the result of a basic model. You generally create a baseline and then try to make more complex solutions in order to get a better result. If you achieve a better score than the baseline, it is good.
•	Logistic Regression.
•	K-Nearest Neighbors (KNN).
•	Random Forest Classifier.

*Tools*
I am using Python language and these packages are:
•	Pandas and Numpy for EDA.
•	Matplotlib and Seaborn for visualization.
•	Scikit-learn for modelling.
