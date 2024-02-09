## Risk Analytics in Banking and Financial Services
This project focuses on analyzing a dataset containing past loan applicants to identify patterns indicative of applicants who may default on loans. The goal is to assist a Consumer Finance Company in understanding the driving factors behind loan defaults, thereby minimizing credit losses.

### Problem Statement
The Consumer Finance Company specializes in providing various types of loans to urban customers. When assessing loan applications, the company must decide whether to approve or reject them based on the applicant’s profile. Defaulting borrowers result in heavy losses for the company, while rejecting potentially repayable loans leads to lost business opportunities.

### Task for Data Analyst
- Importing the dataset of loan applicants from 2007 to 2011.
- Data cleaning to ensure the dataset is suitable for analysis.
- Analysis of the dataset to identify patterns of risky loan applicants through univariate, bivariate, and multivariate analysis.
- Dataset Information
- The dataset contains 39,717 entries and 16 columns, including:
  - funded_amnt: The amount funded by investors
  - term: The term of the loan
  - int_rate: Interest rate on the loan
  - installment: Monthly payment owed by the borrower
  - emp_length: Employment length in years
  - home_ownership: Type of home ownership
  - annual_inc: Annual income of the borrower
  - verification_status: Verification status of the income
  - issue_d: Issue date of the loan
  - loan_status: Current status of the loan
  - purpose: Purpose of the loan
  - addr_state: State of the borrower
  - dti: Debt-to-income ratio
  - delinq_2yrs: Number of delinquencies in the past 2 years
  - open_acc: Number of open credit lines
  - total_acc: Total number of credit lines
  
### Usage

To replicate the analysis:
- Download or clone the repository.
- Ensure you have Python installed along with the necessary libraries (NumPy, Pandas, Matplotlib).
- Open the Jupyter Notebook or Python script containing the analysis.
- Run each cell or section sequentially to reproduce the analysis.
  
### Conclusion
Through exploratory data analysis (EDA), this project aims to uncover insights into the risk factors associated with loan defaults. By identifying patterns within the dataset, the Consumer Finance Company can make informed decisions to mitigate credit losses and optimize their lending process.
