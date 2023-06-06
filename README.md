# Predicting-Fraudulent-Transactions

This case requires trainees to develop a model for predicting fraudulent transactions for a
financial company and use insights from the model to develop an actionable plan. Data for the
case is available in CSV format having 6362620 rows and 10 columns.

## 1. KNN

  Here i have used KNN Model which ia a supervised machine learning algorithm.It classifies and predict a new type of data instances with the simalrity of the training set(instances).So, this model calculates the distance between the new data point and all training instances and further it will selects the K nearest neighbours and conclude the class label or predict the output values based on majority or average of neighbours. 

    **F1 SCORE** for this  - 0.5922182920667004
## 2. Gradient Bossting

The second model i have used here is Gradient Boosting, It is machine learning technique which comes under the ensembling technique. This technique will create a initial model and with simple predictions based on the average value of targeted variable. In further Iteration, the new trees will be added with thecombined prediction previous tree. The New tree is to minimize the errors and residue in the previous trees.

    **F1 Score** for this - 0.7748022755654224 
## 3. ExtremeGB

The third model ihave used here is ExtremeGb.It makes an Optimized Implementaion
from the Gradient Boosting algorithm.It leads us to high performance model.It prevents overfitting.

    **F1 Score** this - 0.7748022755654224

##Variables to Be Included

According to the Data Dictionary of this Statement<

**step** - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

**type** - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

**amount** - amount of the transaction in local currency.

**nameOrig** - customer who started the transaction

**oldbalanceOrg** - initial balance before the transaction

**newbalanceOrig** - new balance after the transaction

**nameDest** - customer who is the recipient of the transaction

**oldbalanceDest** - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

**newbalanceDest** - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

**isFraud** - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

**isFlaggedFraud** - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.
##Key Factors that predict Fradulent Customer

The major key factor i have considerd to predict the Fardulent Customer are:-

Transaction Type, Transaction Amount, Balance Differentials, Customer Behavior(typical pattern of Transaction)

## Kind of prevention should be adopted while company update its infrastructure?

The company should adopt some major preventions and  so it can prevent from fraudelnt activities. So, the Major preventions to be considered are: Robust Authentication and Authorization, Real-Time Monitoring and Alert Systems,
Anomaly Detection and Machine Learning, Transaction Monitoring and Anti-Money Laundering (AML) Procedures, Customer Verification and KYC, Employee Training and Awareness, Regular Security Audits and Assessments.

## Kind of prevention should be adopted while company update its infrastructure?

The company should adopt some major preventions and  so it can prevent from fraudelnt activities. So, the Major preventions to be considered are: Robust Authentication and Authorization, Real-Time Monitoring and Alert Systems,
Anomaly Detection and Machine Learning, Transaction Monitoring and Anti-Money Laundering (AML) Procedures, Customer Verification and KYC, Employee Training and Awareness, Regular Security Audits and Assessments.
