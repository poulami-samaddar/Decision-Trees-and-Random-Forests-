# Decision-Trees-and-Random-Forests-
# Project 1 : Kyphosis disease classification
Kyphosis is an abnormally excessive convex curvature of the spine. The kyphosis data frame has 81 rows and 4 columns. 
* Kyphosis (absent/present)
* Age
* Number
* Start

At first classification is done by training a single Decision Tree and 72% accuracy is achieved. After that random forest classifier is used to predict the outcome (Kyphosis : absent/present). This time the model’s accuracy is 80% (full confusion matrix and classification report is shown in jupyter notbook).  




# Project 2: Lending Club loan classification
This project uses data from LendingClub.com (2007-2010). Lending Club connects people who need money (borrowers) with people who have money (investors). These are the columns of the data set
* credit policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
* int. rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded.
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

The model will predict if the borrowers will pay back the loan depending on the features mentioned above. With single Decision Tree and random forest model respectively  73% and 85% accuracy is achieved (full confusion matrix and classification report is shown in jupyter notbook).  
