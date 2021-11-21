# Loan-Prediction-Model
### Live link :
https://ds-ml-loan-prediction.herokuapp.com/

## Description
Loan Prediction is very helpful for employee of banks as well as for the applicant also. The aim of this Paper is to provide quick, immediate and easy way to choose the deserving applicants.s. Our main objective of this project is to predict the safety of loan. To predict loan safety, the SVM and Naïve bayes algorithm are used. First the data is cleaned so as to avoid the missing values in the data set.
The purpose of this model is to provide a comprehensive research and to develop a model to predict the loan defaults. This kind of models becomes inevitable as the issue of bad loans are very much critical in the financial sector especially in micro financing banks of various underdeveloped and developed countries. To cope up with this problem a comprehensive literature review was done to study the significant factors that leads to this issue. 

## I/O Screenshort
![Screenshot (7)](https://user-images.githubusercontent.com/91031609/142771460-c9b005b9-98e3-4f50-8d7c-624bbdcf360c.png)
![Screenshot (4)](https://user-images.githubusercontent.com/91031609/142771546-c92b23d3-d22b-48e4-bbf9-4e9e1b84c9ea.png)
![Screenshot (3)](https://user-images.githubusercontent.com/91031609/142771559-0edce771-a9ae-4fa7-9340-48b6efa17c79.png)
![Screenshot (6)](https://user-images.githubusercontent.com/91031609/142771566-6ce85264-c911-48c8-88cd-4071709f609d.png)
![Screenshot (5)](https://user-images.githubusercontent.com/91031609/142771570-e6a5b441-2074-49c4-882c-055448a19704.png)

## Proposed Model
This system predict whether the loan is approve or reject . This System refers the following things or ways.
Data Collection
<br>
Data Pre-processing (Data Cleaning)
<br>
Model Selection
<br>
Model Evaluation
<br>
Classification
<br>
Result (output)

## Proposed Algorithm
The following shows the pseudo code for the proposed loan prediction method
<br>
1. Load the data
2. Determine the training and testing data
<br>
3. Data cleaning and pre-processing.
<br>
a) Fill the missing values with mean values regarding numerical values.
<br>
b) Fill the missing values with mode values regarding categorical variables.
<br>
c) Outlier treatment.
<br>
4. Apply the modelling for prediction
<br>
a) Removing the load identifier
<br>
b) Create the target variable (based on the requirement).In this approach, target variable is loan-status
<br>
c) Create a dummy variable for categorical variable (if required) and split the training and testing data for validation.
<br>
d) Apply the model: NB method, SVM method
<br>
5. Determine the accuracy followed by confusion Matrix.

## Flow Chart
![dsproject](https://user-images.githubusercontent.com/91031609/142772221-61768df9-108d-423d-95e0-38745a612cb0.PNG)

## Technologies/Libraries Used
Flask
Jinja2
numpy
scipy
scikit-learn
matplotlib
pandas
Loan Prediction Model powered by Data Science and Machine Learning which is deployed on Heroku through Flask
