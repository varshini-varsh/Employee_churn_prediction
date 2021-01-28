# Employee_churn_prediction

## EMPLOYEE CHURN PREDICTION

Cover the following topics:

* Data loading and understanding feature
* Exploratory data analysis 
* Data visualization
* Cluster analysis
* Building prediction model
* Evaluating model performance
* Conclusion

# 1. Data loading and understanding feature

In Research, it was found that employee churn will be affected by age, tenure, pay, job satisfaction, salary, working conditions, growth potential and employee’s perceptions of fairness. Some other variables such as age, gender, ethnicity, education, and marital status, were essential factors in the prediction of employee churn. In some cases such as the employee with niche skills are harder to replace. It affects the ongoing work and productivity of existing employees. Acquiring new employees as a replacement has its costs such as hiring costs and training costs. Also, the new employee will take time to learn skills at the similar level of technical or business expertise knowledge of an older employee. Organizations tackle this problem by applying machine learning techniques to predict employee churn, which helps them in taking necessary actions.

# 2. Exploratory data analysis

* In Research, it was found that employee churn will be affected by age, tenure, pay, job satisfaction, salary, working conditions, growth potential and employee’s perceptions of fairness. 
* Some other variables such as age, gender, ethnicity, education, and marital status, were essential factors in the prediction of employee churn. 
* In some cases such as the employee with niche skills are harder to replace. It affects the ongoing work and productivity of existing employees. 
* Acquiring new employees as a replacement has its costs such as hiring costs and training costs. 
* Also, the new employee will take time to learn skills at the similar level of technical or business expertise knowledge of an older employee. 
* Organizations tackle this problem by applying machine learning techniques to predict employee churn, which helps them in taking necessary actions.

# Importing Modules
* import pandas  # for dataframes
* import matplotlib.pyplot as plt # for plotting graphs
* import seaborn as sns # for plotting graphs

* i.Loading Dataset
* ii. Expressing data
* iii. Data Insights

# 3. Data Visualization
* i. Employees Left
* ii. Number of Projects
* iii. Time Spent in Company
* iv. Subplots using Seaborn
* v. Data Analysis and Visualization Summary
Following features are most influencing a person to leave the company:

* Promotions: Employees are far more likely to quit their job if they haven't received a promotion in the last 5 years.
* Time with Company: Here, The three-year mark looks like a time to be a crucial point in an employee's career. Most of them quit their job around the three-year mark. Another important point is 6-years point, where the employee is very unlikely to leave.
* Number Of Projects: Employee engagement is another critical factor to influence the employee to leave the company. Employees with 3-5 projects are less likely to leave the company. The employee with less and more number of projects are likely to leave.
* Salary: Most of the employees that quit among the mid or low salary groups.

# 4. Cluster Analysis:
Here, Employee who left the company can be grouped into 3 type of employees:

* High Satisfaction and High Evaluation(Shaded by green color in the graph), you can also call them Winners.
* Low Satisfaction and High Evaluation(Shaded by blue color(Shaded by green color in the graph), you can also call them Frustrated.
* Moderate Satisfaction and moderate Evaluation (Shaded by grey color in the graph), you can also call them 'Bad match'.

# 5. Building a Prediction Model using Gradient Boosting Tree.
* i. Pre-Processing Data
Lots of machine learning algorithms require numerical input data, so you need to represent categorical columns in a numerical column.
In order to encode this data, you could map each value to a number. e.g. Salary column's value can be represented as low:0, medium:1, and high:2.
This process is known as label encoding, and sklearn conveniently will do this for you using LabelEncoder

* ii. Split Train and Test Set
To understand model performance, dividing the dataset into a training set and a test set is a good strategy.
Let's split dataset by using function train_test_split(). You need to pass 3 parameters features, target, and test_set size. Additionally, you can use random_state to select records randomly.

* iii. Model Building
Let's build employee an churn prediction model.
Here, you are going to predict churn using Gradient Boosting Classifier.
First, import the GradientBoostingClassifier module and create Gradient Boosting classifier object using GradientBoostingClassifier() function.

# 6. Evaluating Model Performance
Well, got a classification rate of 97%, considered as good accuracy.
* Precision: Precision is about being precise, i.e., how precise your model is. In other words, you can say, when a model makes a prediction, how often it is correct. In your prediction case, when your Gradient Boosting model predicted an employee is going to leave, that employee actually left 95% of the time.
* Recall: If there is an employee who left present in the test set and your Gradient Boosting model can identify it 92% of the time.

# CONCLUSION
In this REPO,observed that What is Employee Churn?, How it is different from customer churn, Exploratory data analysis and visualization of employee churn dataset using matplotlib and seaborn, model building and evaluation using python scikit-learn package.

I look forward to hearing any feedback or questions. You can ask a question by leaving a comment, and I will try my best to answer it.

