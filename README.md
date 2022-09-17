# Adult_Income_ML-Project
[![author](https://img.shields.io/badge/Author-Rayden_Xu-blue.svg)](https://www.linkedin.com/in/rundong-xu-269012230/) 

| **--->** [Script](/Adult_Income_Project-From-Scratch-/blob/main/Income_Classification_Final.ipynb) | 

| **--->** [Project-Report](/Adult_Income_Project-From-Scratch-/blob/main/ IE7374 Final Project - Lark.pdf.ipynb) |

| **--->** [Presentation-Slide](/Adult_Income_Project-From-Scratch-/blob/main/Pre-7374-final.pdf) |

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
  - EDA
    - Statistical Analysis
    - Univariate Analysis 
    - Using heatmap to conduct binary analysis
    <div align=center>
    <img src="picture/2e8cb05d-af94-4e82-82ef-66ed9881a0f7.png" width="600px">
    </div>
    - Using Pairplot to conduct Multivariate analysis
    <div align=center>
    <img src="picture/e4e412c9-b4d4-47fa-b574-70d6cf41aa32.png" width="600px">
  
### 5.Feature Engineering
- Work Flow
    <div align=center>
    <img src="picture/Feature Engineerning.png" width="600px">
    </div>
  After Data Clean--> EDA --> Feature Engineerning, we have 4 dataset(ad_df, ad_df3, ad_df2, ad_df_GNB) for using.
  
### 6.Algorithm
- The general workflow is that:
  - 1st: Seting ad_df3 as Baseline(Do nothing), and seting others as controll group by different preprocessing step.
  - 2nd: After Feature engineerning, puting all ad_dfx into 5 different algorthim,let ad_df4 alone into GNB(Gaussian assumption). 
  - 3rd: Comparing metrics(Accuracy,recall,precision,F-1 Score).
  - 4th: K-fold cross validation and tuning.
  - 5th: Model selection.
 
<div align=center>
<img src="picture/FlowDiagram.jpg" width="600px">
</div>

#### 7
