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

## Models Used
1) SVM:
In this approach, each data item is plotted in a ndimensional space, where n represents the number of features with each feature represented in a corresponding co- ordinates. A hyper plane is determined to distinguish the classes (possibly two) based on their features.
2) Naïve Bayes (NB) Model :
The basis for NB model is Bayes Theorem (BT), where events are mutually exclusive similar to rolling a die. Moreover, the BT presumes that the input features also referred aspredictors are independent in nature. Similarly, NB also presumes that the input features are independent in nature. But, this is impossible in the realistic procedures.Since this assumption leads to naïve, this algorithm is termed as Naïve Bayes algorithm. Thus, NB is a probabilistic algorithm, where the conditional probability is determined regarding the input features. On the other hand, during the dependent input features scenario, conditional probability is calculated twice resulting in improper results. Hence, for better prediction results with respect to NB model, independent input features are selected and processed.dataset collected from Kaggle source. The feature in the dataset include
1. Aplication_Id
2. Gender
3. Marital Status
4. Number of dependents
5. Educational Profile
6. Employment Status
7. Applicant‘s Income
8. Co-Applicant‘s Income
9. Loan Amount
10. Credit History
11. Loan Status
12. 
## Proposed Algorithm
The following shows the pseudo code for the proposed loan prediction method
1. Load the data
<br>
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

## Use Case Diagram
![image](https://user-images.githubusercontent.com/91031609/142772777-559d0c51-fc2c-4ddf-b521-59c4ae037b71.png)

## Conclusion
So here, it can be concluded with confidence that the Naïve Bayes model is extremely efficient and gives a better result when compared to other models. It works correctly and
fulfills all requirements of bankers. This system properly and accurately calculate the result. It predicts the loan is approve or reject to loan applicant or customer very accuratly.
