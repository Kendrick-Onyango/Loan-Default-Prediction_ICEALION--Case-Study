# Loan-Default-Prediction_ICEALION--Case-Study

###PROBLEM STATEMENT

Credit default risk is the risk that a lender takes the chance that a borrower fails to make required payments of the loan.
The main purpose of this analysis is to predict whether a new customer can be a reliable customer. It's a way to avoid default and increase the bank’s revenue. This can be used to automate approving and declining loan applications more accurately.


----Hypothesis:: Predictiong customer reliabilty interms of loan repayment will avoid default and incraese the banks revenue.

Qestions to be determined.
----analyse the data and visualize the most important features and share three ideas on how to increase the % of successful loan applicants
----Predict the outcome of a loan: is a customer likely to satisfy or default on the loan obligations?

###Data Science Framing of Problem:
Since the nature of problem/challenge is a binary or a dichotomous in nature,To test the hypothesis, Machine Learning Algorithm (Logistic Regression) will be required to predict behaviour of a customer either to default or to pay a aloan

Contribution features such as:

Credit History
Person Income.
Home Ownership

After building the model, we can inspect the model interpretability using Sklearn Feature importance to identify the greatest features that explain the behaviour of a new customer interms of honoring loan obligations. Also to evaluate it's performance with various metrics to see how far the model can predict loan status. For our case we opt to go with confusion matrix and accuracy because target labels are not well balanced.


PART B: EXPLORATORY DATA ANALYSIS(EDA)
After problem and hypothesis framing, the next task was EDA with the dataset given.

Also I did Bivariate & multivariate Analysis on the features to understand the distribution and correlations.

The EDA work and observations can be found in this detailed and separate Notebook attached Main Files

PART C: DATA WRANGLING
After EDA, I understood the data better and the next step was feature engineering. This involved taking a deeper dive into the data and generating new features that would better predict the reaction of the rider on a particular order.


Also some distribution analysis on the generated features using histogram plots.

Work relating to this task can be found in the separate Notebook attached Main Files

PART D: MODEL BUILDING AND EVALUATION
After the features had been formed, I used the polished dataset to build the Regression model. 
Evaluation metrics used are accuracy and confusion matrix

The notebook to the task can be found in the separate Notebook attached Main Files.

REPORTING, INSIGHTS AND RECOMMENDATION
This is where your client sees the value of the work you have been doing. For this, I prepared an executive summary slide detailing the findings, insights and recommendations.

The presentation can be found on this slide.
