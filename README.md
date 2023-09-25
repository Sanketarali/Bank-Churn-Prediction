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

# Bank Churn Prediction model



