## PREDICTING EMPLOYEE RETENTION USING LOGISTIC REGRESSION

## OBJECTIVE
In this assignment we have be built  a logistic regression model to 
predict the likelihood of employee retention based on the data 
such as demographic details, job satisfaction scores, performance 
metrics, and tenure.The aim of this is to provide the HR department with actionable 
insights to strengthen retention strategies, create a supportive work 
environment, and increase the overall stability and satisfaction of 
the workforce.

## ASSIGNMENT STEPS
1. Data Understanding
2. Data Cleaning
3. Train Validation Split
4. EDA on training data
5. EDA on validation data(Optional)
6. Feature Engineering
7. Model Building
8. Prediction and Model Evaluation

## DATA DICTIONARY
The data has 24 Columns and 74610 Rows. Following data dictionary provides the description for each column present in dataset:
 Employee ID: A unique identifier assigned to each employee.
 Age: The age of the employee, ranging from 18 to 60 years.
 Gender: The gender of the employee.
 Years at Company: The number of years the employee has been working at the company.
 Monthly Income: The monthly salary of the employee, in dollars.
 Job Role: The department or role the employee works in (e.g., Finance, Healthcare, Technology, Education, Media).
 Work-Life Balance: Perceived balance between work and personal life (Poor, Below Average, Good, Excellent).
 Job Satisfaction: Satisfaction with the job (Very Low, Low, Medium, High).
 Performance Rating: The employee's performance rating (Low, Below Average, Average, High).
 Number of Promotions: Total number of promotions received.
 Overtime: Number of overtime hours.
 Distance from Home: Distance between the employee’s home and workplace (in miles).
 Education Level: Highest education level (High School, Associate Degree, Bachelor’s, Master’s, PhD).
 Marital Status: Marital status (Divorced, Married, Single).
 Number of Dependents: Number of dependents the employee has.
 Job Level: The job level (Entry, Mid, Senior).
 Company Size: Size of the company (Small, Medium, Large).
 Company Tenure (In Months): Total number of months the employee has worked in the industry.
 Remote Work: Whether the employee works remotely (Yes or No).
 Leadership Opportunities: Availability of leadership opportunities (Yes or No).
 Innovation Opportunities: Availability of innovation opportunities (Yes or No).
 Company Reputation: Employee’s perception of company reputation (Very Poor to Excellent).
 Employee Recognition: Level of recognition received (Very Low, Low, Medium, High).
 Attrition: Whether the employee has left the company.

 ## The expected tasks are as follows:
1. Data Understanding

             Load the data and understand the basic statistical summary of the data

2. Data Cleaning (15 marks)

             2.1 Handle the missing values (10 marks)

             2.2 Identify and handle redundant values within categorical columns (if any) (3 marks)

             2.3 Drop redundant columns (2 marks)

3. Train-Validation Split (5 marks)

             3.1 Split the data into train and validation with a 70:30 ratio

4. EDA on Training Data (20 marks)

             4.1 Perform univariate analysis (6 marks)

             4.2 Perform correlation analysis (4 marks)

             4.3 Check the class balance (2 marks)

             4.4 Perform bivariate analysis (8 marks)

5. EDA on Validation Data (Optional)

6. Feature Engineering (20 marks)

             6.1 Dummy variable creation (15 marks)

             6.2 Feature scaling (5 marks)

7. Model Building (40 marks)

             7.1 Feature selection (5 Marks)

             7.2 Building a logistic regression model (20 marks)

             7.3 Find the optimal cutoff (15 marks)

8. Prediction and Model Evaluation (30 marks)

             8.1 Make predictions over the validation set (15 marks)

             8.2 Calculate the accuracy of the model (2 marks)

             8.3 Create a confusion matrix and create variables for true positive, true negative, false positive and false   negative (5 marks)

             8.4 Calculate sensitivity and specificity (4 marks)

             8.5 Calculate precision and recall (4 marks)



