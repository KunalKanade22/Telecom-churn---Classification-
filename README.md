# Telecom-churn---Classification

![Image rep](https://github.com/KunalKanade22/KunalKanade22/blob/main/Image%20rep/telecom.jpeg)

Telecom Churn Case Study with Decision Tree
A “churn” is a term used majorly in service industries that refers to attrition, a customer shift from one service provider to other due to many reasons. Many industries like Telecom, Media, Insurance, and other subscription-based company do analysis to reduce churn. For Assessment, Telecom data from IBM containing 21 attributes of 7,043 telecommunication customers were provided for analysis (Kaggle,2020). 
The steps taken to build an efficient model are 
1.	Data pre-processing.
2.	 Changing and scaling datatype. 
3.	Dropping attributes which are not essential for analysis. 
4.	Replacing binary information for better analysis.
5.	Exploratory data analysis (EDA) – Univariate and Bivariate analysis.
6.	Model building – With and Without deletion of columns. 
7.	Results overview and important features explained by both models.

# About Project
The aim of this project is to share insight of dataset “Telcom” through various analytical methods. This has been explained by data cleaning, data mining principals to be more specific to take strategic decision based on model prediction and accuracy by using Decision tree as one of the Machine learning technique.


# Business Problem

For the Telcom data set, we have a target variable “Churn” and need to find out what factors influence customers to shift to competitors. 


# Approach

Task 1 – Model Development
There are many factors which need to be considered for model development. In this section, the author will explain the problem statement and steps which are required for pre-processing, data cleaning and data manipulation, and Statistical inferences which will explain the distribution of data across columns followed by EDA which will provide additional insight into our dataset and its relation amongst variables in comparison with our target variable “Churn”. Finally, we will randomly split the data set for model building and we will analyse the results based on our pre-processing. For comparison, two models one with all columns and one with selected columns have been built.


•	Exploratory Data Analysis
In this section, the author was able to find insight into a dataset, Statistical inferences – Like mean, median and standard deviation across its variable. All insights have been explained in detail in Interpretation. 
•	Data Cleaning and Feature Selection
Pre-processing is a very important building block of model building. In our dataset steps have been taken to make standardise data types, change data types, replace data types with binary numbers adding dummy data to certain columns. Performing bivariate analysis for better insights. 
•	Model Building 
Pre-processing data has been used to build two models on the Decision tree using the Scikit-learn machine language library for classification in our case its “churns” In Jupyter notebook.  The measure which has been used is “Entropy” for the homogeneous selection of nodes.  

##Task 2 – Handling Missing Values
Our dataset has 11 missing values from the important variable “Total Charges”. As it's only 0.1% of our dataset. There are many ways we can impute the dataset, If it’s numerical then we can impute by mean, median and mode. For our dataset, I have imputed by using the mean as it shouldn’t impact overall model performance even if we delete the missing values or impute. 
##Task 3 – Interpretation of Churn Analysis
This is our suggestion to businesses to make strategies to improve certain areas to reduce churn. After doing EDA and model building the impacts are as follows. 
 
## •	EDA Interpretation
1.	50% of customers churn within 10 Months of opting in. 
2.	Customer decline after 5 months of using services, which is concerning to the telco company.
3.	26.5% of customers are in churn and have stopped using the services.
4.	Customers with high bills are not churning.
5.	Senior citizen doesn’t churn much as they don’t want to change to other operators.
6.	Younger Members without partners with no dependent tend to churn more than others.
7.	Phone services are a major reason for churning.
8.	Internet services – fibre optics as an internet service tends to churn more compared with other services.
9.	Monthly contract with paperless billing with online payment -churn more. 
10.	Variables – Gender, streaming tv, and streaming movies have negligible impact on churning. 

## •	Model Interpretation
1.	Model 1: - Important Variable is – Total Charges, Contract – month to month and tenure which is driving churn. The model accuracy is 72% with an F1 score of 82%, which means we can correctly identify customers who are likely to churn. 
Suggested Improvement: - 
a.	Correlation among the variable is an important factor, monthly charges and total charges are highly correlated, and one variable needs to be dropped to improve model efficiency. 
b.	Other Machine learning techniques: - We need to test other ML techniques like logistic regression, KNN, and Random Forest and then compare the best model among all. 

