# Business-Case-LoanTap-Logistic-Regression


LoanTap is an online platform committed to delivering customized loan products to millennials. They innovate in an otherwise dull loan segment, to deliver instant, flexible loans on consumer friendly terms to salaried professionals and businessmen.

The data science team at LoanTap is building an underwriting layer to determine the creditworthiness of MSMEs as well as individuals.

LoanTap deploys formal credit to salaried individuals and businesses 4 main financial instruments:

Personal Loan
EMI Free Loan
Personal Overdraft
Advance Salary Loan
This case study will focus on the underwriting process behind Personal Loan only

Loan Default Prediction: Risk-Aware Lending
An end-to-end ML project to predict loan defaults and optimize credit risk using Logistic Regression.

Key Implementation Steps

EDA: Univariate and Bivariate analysis of borrower profiles (income, credit history, loan purpose).

Preprocessing: Outlier capping and StandardScaling to ensure coefficient stability.

Feature Engineering: Created risk flags for Pub_rec, Mort_acc, and Bankruptcies to capture binary risk triggers.

Evaluation: Optimized the model using Precision-Recall Curves to balance interest income vs. Non-Performing Assets (NPAs).

 Business Impact
Precision Focus: Reduces "False Positives" to avoid losing interest income from creditworthy borrowers.

Recall Focus: Maximizes "Defaulter Detection" to prevent capital loss from high-risk NPAs.
