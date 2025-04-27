# Census-Income-Project
To predict whether an individual's income exceeds $50K per year based on census data using machine learning.

# Problem Statement
The objective of this project is to develop a machine learning model that can predict whether a person earns more than $50,000 per year based on their personal and professional attributes.
This is a binary classification problem where the income is categorized as:
<=50K,
>50K
Accurate income prediction can help in areas such as targeted marketing, resource planning, and social policy development.

# Objective

* To explore and understand the demographic factors that influence income levels.

* To preprocess and clean the dataset for machine learning tasks.

* To apply various machine learning models and select the best-performing one.

* To evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

* To fine-tune the best model using hyperparameter optimization techniques

 # Dataset Information

  Feature	               Description
  
* age	                   Age of the individual
  
* workclass	            Type of employment (Private, Self-emp, Govt)
  
* fnlwgt	              Final weight (census statistical weight)

* education	            Education level

* education-num	        Education level in numeric form

* marital-status	      Marital status

* occupation	           Type of job

* relationship	         Relationship status

* race	                 Race

* sex	                   Gender

* capital-gain	         Capital gain
  
* capital-loss	          Capital loss

* hours-per-week	       Hours worked per week
  
* native-country	       Country of origin

*income                 (<=50K or >50K)

# Data Preprocessing
Data preprocessing steps carried out:

1. Handling Missing Values
Some fields like workclass, occupation, and native-country had missing values marked as "?".

These missing values were replaced by the mode (most frequent value) of their respective columns.

2. Encoding Categorical Features
Label Encoding for binary categorical features (sex, etc.).

One-Hot Encoding for multi-category features (workclass, education, occupation, native-country, etc.).

3. Feature Scaling
Continuous variables like age, hours-per-week, capital-gain, and capital-loss were scaled using StandardScaler to normalize the data distribution.

4. Train-Test Split
Data split into training (70%) and testing (30%) sets to evaluate model generalization.

# Exploratory Data Analysis (EDA)
* Age vs Income: Older individuals generally earned more.

* Workclass Analysis: Certain sectors like Federal government had a higher proportion of >50K earners.

* Education Impact: Higher education levels correlated with higher income.

* Gender Bias: Males had a higher probability of earning >50K compared to females.

* Hours-per-Week: Individuals working more hours were likelier to earn more.

* Visualizations like histograms, bar charts, and heatmaps were used to support these findings.

  # Algorithm used
  * Logistic Regression




