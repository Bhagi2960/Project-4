
## Project  Overview

As remote work becomes the new norm, it's essential to understand its impact on employees' mental well-being and productivity. What are the effects of remote work on employee satisfaction and productivity? What factors influence productivity and employee satisfaction with respect to work location? Are employees working fully remote, hybrid or onsite most likely to be satisfied and perform at a higher productivity level? This project seeks to answer the above  questions.  


We used a data set obtained from Kaggle that contained data across various industries and different regions of the world. The data provided valuable insights into how factors such as the number of hours worked, number of virtual meetings, mental health condition and job role affect employee satisfaction and productivity.
This analysis could help businesses, HR professionals, and researchers assess the growing influence of remote work on productivity and well-being and make appropriate decisions so that it would benefit both employees and companies in the long run.



## Group Roles:

Data Clean up – Luke

Data Preprocessing – Bhagi and Luke

Data Analysis/Tableau/graphs etc. – Jay and Maher

Building the ML Model – Neural Network Deep Learning Model – Bhagi

Building the ML Model – Logistic Regression and Random Forest – Luke

Testing the Models – Bhagi and Luke

Creating the Documentation – Bhagi, Luke, Jay, Maher

Creating the Presentation - Jay, Maher,  Luke, Bhagi


## Data Set 

Obtained from Kaggle:  Remote work and mental health.
https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health/data
The original data set consisted of  the following fourteen columns of which productivity and satisfaction were  our target variables and all others were the feature variables.

Feature Variables:
Employee ID, 
Age ,
Gender, 
Job_Role, 
Work_Location, 
Hours Worked Per Week, 
Number of Virtual Meetings, 
Mental Health Condition, 
Access to Mental Health Resources, 
Physical Activity, 
Sleep Quality,
Region

Target Variables : Productivity, Satisfaction

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Data Analysis -- Maher and Jay


**Employee Job Satisfaction Based on Work Location:** 

The data reveals a clear trend: employees working remotely are generally less satisfied, with software engineers being the only exception, showing more satisfaction than dissatisfaction when working from home. In contrast, onsite work presents a more balanced distribution of satisfaction levels, although there is a notable outlier in the sales role, where a significant gap exists between satisfied and unsatisfied employees.
For hybrid work, employee satisfaction is significantly higher across the board. The only exception is the human resources (HR) role, where more employees report dissatisfaction. This trend makes sense, as hybrid work offers the flexibility of both remote and onsite environments, which likely explains the higher contentment levels. However, the nature of HR—requiring close management of business operations—may contribute to the dissatisfaction among HR employees in hybrid roles, as their responsibilities might be better suited to a fully onsite setting.



**Hours worked per week vs. Employee Satisfaction based on Work Location:**

The graph explores the relationship between hours worked per week and employee satisfaction across different work locations. It clearly shows a consistent decline in satisfaction as weekly work hours increase, regardless of whether employees are working hybrid, onsite, or remotely. In other words, as employees work more hours, their satisfaction tends to drop across all work arrangements.
This finding aligns with basic human psychology—when people are overworked, they often experience increased stress, reduced productivity, diminished performance, and even burnout. It’s no surprise that longer work hours lead to a greater sense of burden, negatively impacting overall job satisfaction.



**Work Location vs. Employee Satisfaction:**

This graph illustrates the relationship between work location and employee satisfaction. As anticipated, the data shows that employees are most satisfied when working in a hybrid arrangement, which offers the flexibility of both remote and onsite work. However, one unexpected finding is that onsite employees report higher satisfaction levels than those working remotely. Initially, one might assume that remote workers, who avoid the commute and enjoy greater autonomy, would be more content. Yet, this data suggests that other factors, such as job engagement, workplace culture, and social interaction, may contribute to higher satisfaction for onsite employees. It’s also possible that some remote workers experience isolation or blurred boundaries between work and personal life, which could negatively impact their overall satisfaction.
It’s important to recognize that our analysis reflects a general trend, and individual satisfaction can vary significantly based on personal preferences and specific job roles.



**Mental Health Condition Based on Region:**

In North America, burnout emerges as the most prevalent mental health condition in the workplace. This aligns with data showing that the U.S. is one of the most overworked developed nations. According to the International Labour Organization, “Americans work 137 more hours per year than Japanese workers, 260 more hours than British workers, and 299 more hours than French workers.”
An unexpected finding from the data is that depression is the leading mental health condition in South America. This can likely be attributed to several factors, including socioeconomic challenges, high stress levels, limited access to mental healthcare, cultural stigma surrounding mental health, and frequent exposure to traumatic events such as violence.

Sleep Quality Based on Region & Age:
Color shows details about Sleep Quality.  The marks are labeled by Region, average of Age, Age Separation  and Work Location.  
Details are shown for Work Location. The data is filtered on Job Role. The view is filtered on Region, Age Separation  and Sleep Quality. 
The Age Separation  filter keeps 18-29, 30-39 and 40-49. The Sleep Quality filter keeps Average, Good and Poor.

**Satisified with Remote Work**

This analysis examines the satisfaction levels of employees with remote work arrangements, segmented by age group and job role. The data highlights 
average ages across various roles within four distinct age groups: 18-29, 30-39, 40-49, and 50-60. Understanding these trends can provide valuable 
insights into how different demographics perceive remote work and its effectiveness in their respective roles.
--Overview of Findings
The data reveals a clear trend: as age increases, so does the average age of employees in each job role. This may indicate varying levels of 
adaptability to remote work based on both age and professional experience. Below is a detailed breakdown of the findings by age group.
Age Group Analysis
1. Age Group 18-29
Insights:
Employees in this age group are predominantly in entry-level or early-career positions, with average ages ranging from approximately 25 to 26 years. 
Their relatively young age suggests they may be more adaptable to remote work technologies and practices, potentially leading to higher satisfaction 
levels due to flexibility and work-life balance.
2. Age Group 30-39
Insights:
This group shows a slight increase in average age, reflecting more experienced professionals who may have established preferences for work environments. 
The roles here are likely to involve more responsibility, which could influence their satisfaction with remote work based on the degree of collaboration 
required in their positions.
3. Age Group 40-49
Insights:
Employees in this age group are approaching mid-career stages, with average ages around mid-40s across all roles. Their experience may lead to a preference 
for established workflows and face-to-face interactions, which could affect their overall satisfaction with remote work setups.
4. Age Group 50-60
Insights:
This older demographic shows the highest average ages across all roles, indicating a wealth of experience but potentially a lower adaptability to remote work 
due to established habits and preferences for traditional office environments. Their satisfaction may hinge on how well remote work accommodates their needs 
for communication and collaboration.
Conclusion
The analysis indicates that employee satisfaction with remote work varies significantly across age groups and job roles:
Younger employees (18-29) are likely to embrace remote work due to their adaptability and desire for flexibility.
Mid-career employees (30-39) may appreciate the balance between flexibility and collaboration but could have mixed feelings depending on their specific role
 requirements.
Older employees (40-60) might face challenges adjusting to remote work, impacting their overall satisfaction levels.

**Unsatisfied with Remote Work**
The analysis focuses on employee satisfaction with remote work across different age groups and job roles, revealing distinct trends in average ages among 
various positions. This data can provide insights into how age influences perceptions of remote work satisfaction.
Age Group Breakdown
1. Age Group 18-29
Average Ages: Ranging from 24.77 (HR) to 26.16 (Software Engineer).
Insights:
This group consists of relatively younger employees, with an average age just above mid-20s.
Roles such as Data Scientist and Designer are prevalent, suggesting a strong presence of tech-savvy individuals who may be more adaptable to remote work environments.
2. Age Group 30-39
Average Ages: Ranging from 34.07 (Marketing) to 35.03 (Software Engineer).
Insights:
Employees in this age group are entering their prime career years, often balancing professional growth with personal responsibilities.
The slight increase in average age compared to the younger group may indicate a growing need for stability, which could influence their satisfaction 
levels with remote work.
3. Age Group 40-49
Average Ages: Ranging from 43.83 (Data Scientist) to 45.41 (Marketing).
Insights:
This group shows a marked increase in average age, suggesting a shift toward more experienced professionals.
The higher averages may correlate with increased expectations for work-life balance and job security, potentially leading to greater dissatisfaction 
if remote work does not meet these needs.
4. Age Group 50-60
Average Ages: Ranging from 54.03 (Project Manager) to 56.04 (Marketing).
Insights:
Employees in this age group are likely nearing retirement or considering long-term career transitions.
Their higher average ages could reflect a preference for traditional work environments and face-to-face interactions, which might contribute to 
dissatisfaction with remote work setups.
Conclusion
The analysis indicates that employee satisfaction with remote work varies significantly across age groups and job roles. Younger employees (18-29) 
appear more adaptable to remote work, while older employees (50-60) may prefer traditional office settings due to established career patterns and 
social interaction needs.

**Comparative Analysis of Employee Satisfaction with Remote Work by Age Group & Job Role**
This analysis examines the differences in employee satisfaction with remote work across various age groups and job roles, based on average ages 
derived from two datasets: one for employees satisfied with remote work and another for those unsatisfied. The findings reveal notable trends that 
can inform organizational policies regarding remote work.
Overview of Data
The data is categorized by age groups (18-29, 30-39, 40-49, and 50-60) and job roles (Data Scientist, Designer, HR, Marketing, Project Manager, 
Sales, Software Engineer). Each role is represented by an average age for both satisfied and unsatisfied employees.

**Correlation for Age & Satisfied vs Unsatisfied with Remote Work based on Region**
In the Analaysis,the data is categorized by age groups and job roles.
The analysis reveals significant regional disparities in satisfaction levels among different age groups. For instance the younger 
demographic (18-29) in Asia appears to be relatively more satisfied compared to their peers in North America, where dissatisfaction 
is notably high. Conversely, the next age demographic (30-39) generally experiences lower satisfaction across most regions, with 
South America showing an intriguing exception.

**Correlation for Gender & Satisfcation with Remote Work**
In this analysis, we examine the correlation coefficients for different age groups and genders regarding their satisfaction with remote work
using the CORR Function. 
Interpretation of Results
1. Age Group Insights:
The 30-39 age group shows the highest correlation for males (0.2425), indicating a stronger relationship between this demographic and their 
satisfaction with remote work compared to other age groups.
The 18-29 age group has the highest correlation for non-binary individuals (0.1238), suggesting that this group may experience unique satisfaction dynamics.
2.	Gender Differences:
Males in the 30-39 age group exhibit significantly higher satisfaction correlation compared to females (0.0757) in the same group.
Across all age groups, non-binary individuals consistently show varying levels of correlation, with their highest being in the youngest age bracket.
3.	Overall Trends:
Most correlations are low, indicating that while there are some relationships between age, gender, and satisfaction with remote work, they are not strong




-----------------------------------------------------------------------------------------------------------------------------------------------------------------












## Machine Learning Models -- Bhagi and Luke

Our goal was to create a model with a high accuracy score. We explored the neural network deep learning model and as the accuracy was not optimal for this data set, we also explored two other models which were a Logistic Regression Mode and a Decision Tree Model.

**Neural Network Model: Deep Learning Model**

NN Deep Learning Modeling Process:

•	We split the data set, scaled and standardize each feature.

•	Fitted the model to our training data

•	Transformed the data

•	Created a sequential model

•	Compiled and ran Model

•	Created accuracy report

NN Model Definition

We ran several iterations our NN model by changing parameters to find the optimal setting with the highest accuracy:

Our Optimal Model Definition:

Input Layer: 33 Neurons

Hidden Layer 1: 40 Neurons

Hidden Layer 2: 40 Neurons

Hidden Layer 3: 20 Neurons

Output Layer: 1

Epochs: 30

•	The best accuracy we could obtain was 0.52 (52% )with a loss of 1.12 which is not optimal.

•	We tried to improve accuracy by increasing the number of neurons per hidden layer, Increasing the number of hidden layers, changing the number of epochs and none of these methods seem to improve accuracy

Possible Reasons for Low Accuracy:

1)Over Fitting: We believe the data adjusted too much to fit the training data and did not generalize well when fitting and predicting test data

2)Another possible cause could be the uniformity of data specifically the non categorical data in which the unique values were distributed evenly among the population and hence lack of variability in the dispersion.

3)To further improve accuracy we evaluated two additional models to see if the accuracy would improve with the same data,. The models we built and evaluated were  a logistic regressions model and a Decision Tree Model.



**Logistic Regression Model Process:**

•	Split the data set, scaled, and standardized each feature

• Applied Principal Component Analysis

•	Fit the model to our training data

•	Obtained predictions using the testing data

•	Created accuracy report and confusion matrix

Logistic Regression Model Accuracy: 51.45%

Possible Reasons for Low Accuracy:

1) The target labels (Productivity and Satisfaction) have low or no linear correlation with the features

**Decision Tree Model Process:**

•	Split the data set, scaled, and standardized each feature

•	Fit the model to our training data

•	Obtained predictions using the testing data

•	Created accuracy report and confusion matrix

• Created a plot of the Decision Tree using Matplotlib

Decision Tree Model Accuracy: 48%

Possible Reasons for Low Accuracy:

1) Overfitting due to the dataset's uniform distribution among its features
