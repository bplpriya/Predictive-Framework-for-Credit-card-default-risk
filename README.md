# Project Title
Predictive-Framework-for-Credit-card-default-risk

# About the dataset
In 2006, Taiwan the credit card issuers faced cash and credit card debt crisis.Taiwanese card-issuing banks overissued cash and credit cards to ineligible applicants in an effort to gain market dominance. At the same time, the majority of cardholders accrued significant credit and cash-card debts due to their excessive use of credit cards for consumption, regardless of their capacity to repay the loan. The crisis dealt a serious damage to consumer trust in finance, and it presents a significant challenge to cardholders as well as banks.

# Dataset
The dataset is taken from UC Irvine Machine Learning Repository(https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients). It has 25 attributes and 30,000 tuples. Seven machine learning models (SGD, Decision Tree, Logistic Regression, KNN, Random Forest, SVM, XGBoost) are used to predict whether the credit card holders are credible or not credible clients.

1. ID: ID of each client
2. LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
3. SEX: Gender (1=male, 2=female)
4. EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)
5. MARRIAGE: Marital status (1=married, 2=single, 3=others)
6. AGE: Age in years
7. PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months,8=payment delay for eight months, 9=payment delay for nine months and above)
8. PAY_2: Repayment status in August, 2005 (scale same as above)
9. PAY_3: Repayment status in July, 2005 (scale same as above)
10. PAY_4: Repayment status in June, 2005 (scale same as above)
11. PAY_5: Repayment status in May, 2005 (scale same as above)
12. PAY_6: Repayment status in April, 2005 (scale same as above)
13. BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
14. BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
15. BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
16. BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
17. BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
18. BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
19. PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
20. PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
21. PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
22. PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
23. PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
24. PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
23. default.payment.next.month: Default payment (1=yes, 0=no)

# About project
Data is cleaned and transformed. Different percentages of train test split (90% and 10%, 80% and 20%, 70% and 30%, 60% and 40%, 50% and 50%) is performed. Comparative Analysis is done on all models of all train test splits using classification metrics. It is compared using ROC curve.

# Result
When percentage of train test split is 80% and 20%, 60% and 40% - Stochastic Gradient Descent has highest accuracy, which is 83.3%.
When percentage of train test split is 70% and 30% - SVC has highest accuracy, which is 83.66%.
Demographics: We see that being female, more educated, single and between 30-40 years old means a customer is more likely to make payments on time.
