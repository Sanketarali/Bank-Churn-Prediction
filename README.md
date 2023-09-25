# Bank-Churn-Prediction
This repository contains code and resources for predicting customer churn in a bank. Customer churn,


# Prerequisites
<h3>To run this project, will need the following:<br></h3>

Python 3.x<br>
Jupyter Notebook<br>
scikit-learn library<br>
pandas library<br>
numpy library<br>

<h3>given some information about dataset like:</h3><br>
 
  RowNumber        
  CustomerId       
  Surname          
    CreditScore       
    Geography       
    Gender           
    Age               
    Tenure           
    Balance          
   NumOfProducts      
  HasCrCard       
   IsActiveMember     
 EstimatedSalary 
   Exited

   # How  did I do?
   <h3>The dataset I am using for the Bank Churn prediction task is downloaded from Kaggle. Now let’s start with this task by importing the necessary Python libraries and dataset:<br></h3>
   
import pandas as pd<br>
import numpy as np<br>
data = pd.read_csv('Churn_Modelling.csv')
data.head()<br>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/85087402-bce1-4826-b7c3-0ed2dce39988)

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/2f503872-bcee-40fc-85de-3fd86dbbc4ee)

<h3>Now before moving forward, let’s have a look at whether this dataset contains any null values or not:<br></h3>

data.isnull().sum()<br>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/902fb11f-9a22-463e-aa8d-b0dac9e842a6)


<h3>The dataset doesn’t have any null values</h3>

<h3> Dropping Irrelevant Features</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/c6510a83-1f06-458e-9ffb-33f7d83e0460)

<h3>Encoding Categorical Data</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/bcc9d123-e870-4203-aa74-0b9d234a8b0f)

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/59d01444-56c6-4fbe-a30e-ed0e9a1c1926)

<h3>Not Handling Imbalanced</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/ea248359-a80c-4da1-828a-80668ba5e17b)

<h3>Handling Imbalanced Data With SMOTE</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/2806c0fb-0773-4b38-b67f-a5277e3948aa)

<h3>Splitting The Dataset Into The Training Set And Test Set</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/86ae59ad-d5d4-48b9-b99d-b2ef80aa64ea)

<h3>Importing the Models</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/5b7a9fe6-adf3-4be9-8cd9-ae9601807047)

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/c568d234-3aba-4049-8e06-da778ae834ee)

<h3>Prediction on Test Data</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/4a3bacf2-8f01-4928-972b-fc7dc2d04512)

<h3>Evaluating the Algorithm</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/8b008ecc-f9b7-4b89-aa5f-c7a461a4646b)

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/04401ab7-17af-408b-b4e1-445e9fbf69f4)

<h3>. Save The Model</h3>

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/3ebd15ed-209d-45b9-955b-7350736fb7ce)

![image](https://github.com/Sanketarali/Bank-Churn-Prediction/assets/110754364/fdade11f-2dd4-438c-bfe0-3251722856c0)









