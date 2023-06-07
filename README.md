# Lending Club Case study.
> Use the concepts of EDA to decipher which types of customers default on the loan.

## Attachments provided:
* Sai_Manish_Akula_LendingClub_CaseStudy_EDA.ipynb
* Sai_Manish_Akula_LCC.pptx

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club (LC) which specialises in lending various types of loans to urban customers. When the company receives a loan application, the  company has to make a decision for loan approval based on the applicant’s profile. 
- When a person applies for a loan, there are two types of decisions that could be taken by the company: "Loan accepted" or "Loan rejected"
- If the company approves the loan, there are 3 possible scenarios: 1) Fully paid, 2) Current and 3) Charged-off/Defaulted
- The company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
- To use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Data Set
- Real data from lendingclub.com has been taken. It is divided into 1 main dataset and a description file of variables for the analysis.

## Process Flow
- There are four major parts that are followed in this case study:
  1. Data understanding
  2. Data cleaning (cleaning missing values, removing redundant columns etc.)
  3. Data Analysis
  4. Recommendations

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Key Assumptions
- Loan_status is used as an Target variable.
- Below set of variables are considered as customer behavioural variables and so required from data set and not considered for Analysis
   ['last_credit_pull_d', 'last_pymnt_amnt', 'last_pymnt_d', 'collection_recovery_fee', 'recoveries’, 'total_pymnt', 'total_pymnt_inv', 'total_rec_prncp', 'total_rec_int', 'total_rec_late_fee’,   'revol_bal', 'revol_util', 'total_acc', 'out_prncp', 'out_prncp_inv', 'open_acc','delinq_2yrs’,  'earliest_cr_line', 'inq_last_6mths','pub_rec’]

## Conclusions
- Though lending money at higher interest rate is profitable to the firm, at same time it can be dangerous as well as number of defaulters goes up. 
  Hence
	 The LC should not lend loans to people who fall in G or F or E grade as they are likely to default and they have higher interest rate.
	 While lending loans for these graded people, "purpose" should also be kept in consideration as above 15% interest rate purposes like credit_card, Small    Business, debt_consolidation and home_improvement have more tendency to default.
- The LC should ensure that those who are being lent the loans at higher interest rates should have a higher income and low DTI. 
- Loan amount should be decided by factoring it against the DTI, annual income , interest rates/ grade, purpose and number of installments.
- Income Verified people are likely to default more than the non-verified people which throws light on income verification process. This process needs to be improved. Additionally along with income verification, home_ownership verification must also be done as own home_ownership are also tending to default more.
- The people with low annual income have higher DTI and therefore more likely to default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Different libraries namely: Numpy,Pandas, Matplotlib and Seaborn
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
