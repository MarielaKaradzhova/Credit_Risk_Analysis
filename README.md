# Predicting Credit Risk with Supervised Machine Learning 

![](https://github.com/MarielaKaradzhova/Credit_Risk_Analysis/blob/main/resources/cr.jpg)

### Tools
 - Python
 - Jupyter Notebook

## Project Purpose

This project displays an overview of the performance of all the machine learning models* used to asses and predict credit risk from the [dataset](https://github.com/MarielaKaradzhova/Credit_Risk_Analysis/blob/main/LoanStats_2019Q1.csv) provided, with the purpose of reducing financial risk for banks and financial institutions. In addition, using a supervised machine learning model can provide portfolio management for clients and recommendations in cases of fraud.


### Machine Learning Models (Algorithms)
 - Logistic Regression
 - Decision Tree
 - Random Forest
 - Support Vector 

##  Analysis Results
Intial view of balance target values:

![](https://github.com/MarielaKaradzhova/Credit_Risk_Analysis/blob/main/resources/df_bal.png)

 - This image shows that low risk = 68470, and high risk = 347. There are more cases of low risk compared to high risk. 

### Balance Accuracy Scores of Machine Learning Models

 **Oversampling** 
1. **RandomOverSampler** 


![](https://github.com/MarielaKaradzhova/Credit_Risk_Analysis/blob/main/resources/rm_ovs.png)
 
*Balanced Accuracy Score: 0.65*
*Precision:*
 - High = predicts low risk
 - Low = predicts high risk
 
*Sensitivity:*

 -0.69 for both high risk and low risk 


 
2. **SMOTE**


![](https://github.com/MarielaKaradzhova/Credit_Risk_Analysis/blob/main/resources/smt.png)

 
*Balanced Accuracy Score:*
-0.66

*Precision:*
-

*Sensitivity:*



3. **Undersampling**


 ![](https://github.com/MarielaKaradzhova/Credit_Risk_Analysis/blob/main/resources/under.png)
 
  
*Balanced Accuracy Score:*
 - 0.58

*Precision:*

*Sensitivity:*


**Combination (Over and Under) Sampling**
4. **SMOTEENN**


![](https://github.com/MarielaKaradzhova/Credit_Risk_Analysis/blob/main/resources/smoteenn.png)

 
*Balanced Accuracy Score:*
-0.646

*Precision:*

*Sensitivity:* 




