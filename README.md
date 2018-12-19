# Predicting-Loan-Defaulting-Clients

This project was implemented using **pyspark** and concepts of **machine learning**

The aim of the project is to predict the clients that may potentially default on loan repayments and is based on the data of customers default payments in Taiwan.
<br></br>

The binary variable to be predicted is 'default payment' (Yes = 1, No = 0). The following 23 variables are the independent variables available in the dataset:

  * **Amount of the given credit (NT dollar)**: it includes both the individual consumer credit and his/her family (supplementary) credit. 
  * **Gender** (1 = male; 2 = female). 
  * **Education** (1 = graduate school; 2 = university; 3 = high school; 4 = others). 
  * **Marital status** (1 = married; 2 = single; 3 = others). 
  * **Age** (year). 
  * **History of past payment**: The past monthly payment records (from April to September, 2005) as follows:   
  * **The repayment status** X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005 ... X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months ... 8 = payment delay for eight months; 9 = payment delay for nine months and above. 
  * **Amount of bill statement (NT dollar)**. X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005 ... X17 = amount of bill statement in April, 2005. 
  * **Amount of previous payment (NT dollar)**. X18 = amount paid in September, 2005; X19 = amount paid in August, 2005 ... X23 = amount paid in April, 2005. 
<br></br>


**Gradient Boosting Classifier** gave the best accuracy of **77.16%** of predicting the defaulters for the next month.


### Data available at :
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
<br></br>

### References:
Yeh, I. C., & Lien, C. H. (2009). The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients. Expert Systems with Applications, 36(2), 2473-2480.
