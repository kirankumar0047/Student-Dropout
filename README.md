# Student's Dropout Prediction using Supervised Machine Learning Classifiers
A Data science project on Predicting Students' dropout using Machine Learning classification models

### Introduction ###
The goal of this project is to develop a predictive model using machine learning classification algorithms to identify students who are likely to drop out. By leveraging data on student demographics, academic performance, socio-economic factors, and other relevant variables, the aim is to build a robust predictive model that can effectively forecast the likelihood of students dropping out. 

The data gathered are from both internal and external sources, pulling information from different institutions. This data was drawn from various databases within universities and colleges. It covers student records spanning from the academic year 2008/2009 to 2018/2019.

This model can then be used by educational institutions to allocate resources, implement early intervention strategies, and support at-risk students.

### Problem ###
In today's educational landscape, student retention and success are of utmost importance for educational institutions. Identifying students who are at risk of dropping out and implementing timely interventions can greatly contribute to improving graduation rates and ensuring academic success. 
What are certain factors that may affect students' retention or dropout in academic institutions?

### Methodology Approach ###
The methodology adopted during the course of this project includes:
* Data collected through [Kaggle datasets](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention). 
* Data processing and descriptive analysis
* Exploratory Data Analysis using Python visualization tools to gain insights into the data and identify any patterns or trends.
* Predictive analysis using Machine Learning Classification algorithms.

### Dependencies ###
* Data Wrangling and processing Libraries
    * Pandas
    * Numpy
* Visualization Libraries
    * Matplotlib
    * Plotly express
    * Plotly Graph Objects
* Machine Learning Libraries
    * Scikit Learn

### Deliverables ###
* Comprehensive Jupyter notebooks containing codes and results

### Findings/Results ###
Through analysis, it is deduced that two factors are to be considered when predicting the student's retention/dropout (not limited to):
* Age at enrollment
* Course
Others that showed significance are:
* Tuition fees up to date
* 1st and 2nd Semester performance
* Application mode

Out of five classification algorithms, the classifier that performed best after several tries was Decision Tree with an 83% accuracy and 0.78 AUC score
