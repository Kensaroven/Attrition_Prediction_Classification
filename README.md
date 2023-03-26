# Attrition_Prediction_Classification

##### **Problem Statement**
Our client is ABC a leading firm and is doing well in the sector. It is recently facing a steep increase in its employee attrition . Employee attrition has gone up from 14% to 25% in the last 1 year . We are asked to prepare a strategy to immediately tackle this issue such that the firm’s business is not hampered and also to propose an efficient employee satisfaction program for long run. Currently, no such program is in place . Further salary hikes are not an option.

##### **Data Description**
The dataset consists of 1470 observations and 8 variables. Each row in dataset represents an employee; each column contains employee attributes:

Independent Variables were:

- Age: Age of employees,
- Department: Department of work,
- Distance from home,
- Education: 1-Below College; 2-College; 3-Bachelor; 4-Master; 5-Doctor;
- Education Field
- Environment Satisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;
- Job Satisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;
- Marital Status,
- Monthly Income,
- Num Companies Worked: Number of companies worked prior to IBM,
- Work Life Balance: 1-Bad; 2-Good; 3-Better; 4-Best;
- Years At Company: Current years of service in IBM

Dependent Variable was:
- Attrition: Employee attrition status(0 or 1)

##### **Techniques used in Classification**
Experimented with 
- Variable Selection techniques
- Logistic Regression

![alt text](https://github.com/Kensaroven/Attrition_Prediction_Classification/blob/main/Logistic%20CF.png?raw=true)

- Decision Trees

![alt text](https://github.com/Kensaroven/Attrition_Prediction_Classification/blob/main/Decision%20Tree%20CF.png?raw=true)

- Random Forest

![alt text](https://github.com/Kensaroven/Attrition_Prediction_Classification/blob/main/Random%20Forest%20CF.png?raw=true)

- K Nearest Neighbours

![alt text](https://github.com/Kensaroven/Attrition_Prediction_Classification/blob/main/KNN%20CF.png?raw=true)

- K-Means Clustering

![alt text](https://github.com/Kensaroven/Attrition_Prediction_Classification/blob/main/KMeans%20CF.png?raw=true)

along with grid tuning to understand hyper parameters

##### **Techniques used in Ensemble Methodologies**
- Voting Classifier
- Averaging
- Weighted Average
- Bagging
- Boosting


## Evaluation metrics


| Method | AUC | Precision | Recall | F1Score | Accuracy |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 0.717 | 0.221 | 0.641 | 0.328 | 0.653 |
| Decision Trees  | 0.584 | 0.221 | 0.641 | 0.328 | 0.653 |
| Random Forest  | 0.664 | 0.5 | 0.076 | 0.133 | 0.867 |
| KNN  | 0.620 | 0.444 | 0.205 | 0.280 | 0.860 |

KMeans  - Silhouette Score (2 clusters) = 0.7079


