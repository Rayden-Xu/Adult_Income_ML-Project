# Adult_Income_ML-Project
[![author](https://img.shields.io/badge/Author-Rayden_Xu-blue.svg)](https://www.linkedin.com/in/rundong-xu-269012230/) 

| **Go to Script--->** [Adult_Income_Project](/Adult_Income_Project-From-Scratch-/blob/main/Income_Classification_Final.ipynb) | 

## 1.Introduction
- **Objective**: Basically, in this project, the objective of this machine learning project is to predict whether a person makes over 50K a year. We are going to focus on building an 'income' classification model. All of these are the prerequisite of default risk modeling.
- **Method**: For one thing, we apply EDA to understand data from univariate to multivariate analysis, apply Feature Engineering to Bining, encode and scaling, also apply hypothesis testing to do feature selection. For another, we write 7 algorithms scratch without using Sklearn, which includes 1 dimension reduction, and 6 classification algorithms to train our model and evaluate the goal by metrics. 
- **Comparation**: Finally, we set the 4 dataset scenario including baseline(ad_df)and the other 3 dataset by improvement, and compare the model from metrics perspective, bias-variance-tradeoff perspective, optimization perspective and space and time consumption perspective to conduct model selection and explore the interpretability.
## 2.Bussiness Value
- All we know that We are naked in Big data society, The user information are collected in every APP and Website includes data on age, gender, country of origin, marital status,marriage, education etc.) when we login in to them.
- Typically, all of this information(Data Asset) would be widely used by Bank, Fintech company and IBD for deciding whether to approve their application of card and account,  evaluating cardholder's credit, anticipating risk of default and fraud in finance, differentiating the value of bond or interest and commission rate for different applicators and even introducing typical monetization method--- ***Advertisement***.
### 3.About Data 
- Data Source： [Adult_data_UCI](/https://archive.ics.uci.edu/ml/datasets/adult) 
- It is the multivariable data set. And it has 48842 instances and 14 attributes. Among the15 indicators, 6 indicators are continuous indicators, and the remaining 9 indicators are discrete indicators.
### 4.Preprocessing
### 5.Algorithm
![Workflow&Framework](/Adult_Income_Project-From-Scratch-/blob/main/picture/FlowDiagram.jpg)
#### 5.1 
