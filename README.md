# dataMiningUsingR-CreditAnalysis

The recent slowdown of the US economy is due in a sizeable degree to the process of extending credit to people who defaulted on their loans (typically mortgages for their houses) as they were not able to repay them. Combined with decreasing real estate prices, many of the institutions that extended the loans ended up owning property that has decreased in value, and therefore lost significant amount of money.  
In the spreadsheet credit3.xls under the tab “Data”, you will find Data pertaining to 1000 personal loan accounts at a bank. The tab “Data Dictionary” contains a description of what the various variables mean. 
When a new applicant applies for credit, as a part of the application, the company collects information which is available in the form of Variables 2 to 21. The company then decides an amount to be credited (the variable CREDIT_EXTENDED.) For these 1000 accounts, we also have information on how profitable did each account turn out to be (variable NPV). A negative value indicates a net loss and this typically happens when the debtor defaults on his/her payments.

The goal in this case is to investigate how one can use this data to better manage the bank's credit extension program. Specifically, our goal is to develop a classification regression model to classify a new account as “profitable” or “not profitable”. 

Methods Used:

Credit_NPV_Analysis_1
1. k-NN
2. Naive Bayes
3. Logistic Regression

Credit_NPV_Analysis_2:
1. Classification Tree
2. Regression Tree
3. Multiple Linear Regression
4. Boosting, Bagging, Random Forests

Credit_NPV_Analysis_3:
The bank has been making losses on this category of loans and the broader purpose of the study is to investigate how one can use this data to better manage the bank's credit extension program. Specifically, our goal is to use association rules to determine what features of applicants are associated with a new account being profitable or not profitable. We will also use cluster analysis to examine whether we can build a small number of profiles of applicants for loans. The latter would be of interest if the bank wanted to develop a better understanding of who its customers are, and what features lead to unprofitable loans.

For reasons discussed before, continue to exclude CREDIT_EXTENDED from your analysis

Methods Used:
1. k-means Clustering
2. Association Rules
3. Combining Cluster Analysis and Association Rules
