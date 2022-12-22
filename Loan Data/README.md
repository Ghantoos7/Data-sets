# Loan Data

This dataset consists of more than 9,500 loans with information on the loan structure, the borrower, and whether the loan was pain back in full. This data was extracted from LendingClub.com, which is a company that connects borrowers with investors.

## Data Dictionary

| Variable  | class     | description                    |
|:----------|:----------|:-------------------------------|
| credit_policy   | numeric | 1 if the customer meets the credit underwriting criteria; 0 otherwise. |
| purpose      | character | The purpose of the loan. |
| int_rate      | numeric   | The interest rate of the loan (more risky borrowers are assigned higher interest rates).  |
| installment  | numeric   | The monthly installments owed by the borrower if the loan is funded. |
| log_annual_inc | numeric   | The natural log of the self-reported annual income of the borrower. |
| dti | numeric   | The debt-to-income ratio of the borrower (amount of debt divided by annual income). |
| fico | numeric   | The FICO credit score of the borrower. |
| days_with_cr_line | numeric   | The number of days the borrower has had a credit line. |
| revol_bal | numeric   | The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle). |
| revol_util | numeric   | The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available). |
| inq_last_6mths | numeric   | The borrower's number of inquiries by creditors in the last 6 months. |
| delinq_2yrs | numeric   | The number of times the borrower had been 30+ days past due on a payment in the past 2 years. |
| pub_rec | numeric   | The borrower's number of derogatory public records.
| not_fully_paid | numeric   | 1 if the loan is not fully paid; 0 otherwise.  |

[Source](https://www.kaggle.com/itssuru/loan-data) of dataset.

-------------------

## Don't know where to start? 

**Challenges are brief tasks designed to help you practice specific skills:**
 
- 🗺️ **Explore**: Generate a correlation matrix between the numeric columns. What columns are positively and negatively correlated with each other? Does it change if you segment it by the purpose of the loan?
- 📊 **Visualize**: Plot histograms for every numeric column with a color element to segment the bars by `not_fully_paid`.
- 🔎 **Analyze**: Do loans with the same purpose have similar qualities not shared by loans with differing purposes? You can consider only fully paid loans.

**Scenarios are broader questions to help you develop an end-to-end project for your portfolio:**

You recently got a job as a machine learning scientist at a startup that wants to automate loan approvals. As your first project, your manager would like you to build a classifier to predict whether a loan will be paid back based on this data. There are two things to note. First, there is class imbalance; there are fewer examples of loans not fully paid. Second, it's more important to accurately predict whether a loan will not be paid back rather than if a loan is paid back. Your manager will want to know how you accounted for this in training and evaluation your model.

You will need to prepare a report that is accessible to a broad audience. It will need to outline your motivation, analysis steps, findings, and conclusions.
