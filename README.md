# Lending Club Case Study
This project involves a comprehensive Exploratory Data Analysis (EDA) of the Lending Club dataset with the objective of uncovering insights into how various consumer and loan attributes influence the tendency of borrowers to default. 
Lending Club, a peer-to-peer lending platform, provides a rich dataset encompassing numerous factors such as loan amounts, interest rates, employment information, credit history, and more.
The main objective is to be able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Steps](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss).
  The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.
  In this case, the customers labelled as 'charged-off' are the 'defaulters'.
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- The dataset contains the complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps
   #### Step1: Data Cleaning.
   #### Step2: Univariate Analysis 
   #### Step3: Segemented Univariate Analysis
   #### Step4: Bivaraiate/Multivariate Analysis
   #### Step5: Results

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Columns used
Based on the data visualization of each and every columns we can select some columns and our next exercise can be limited to those columns 
Required column lists: 

		a. funded_amnt, (Loan Attributes) - Loan Amount issued to borrower
		b. Id or Member_id  - ID assigned to the borrower of loan id
		c. Term  (Loan Attributes) - Duration of the loan
		d. Int_rate  (Loan Attributes) - Interest rate of the loan
		e. Installment  (Loan Attributes) - monthly installment to be paid by the borrower
		f. Verification_status  (Loan Attributes) - verification status of the document before approving the loan 
		g. Home_ownership  (Consumer attribute) - Home type of the borrower 
		h. Annual_inc (Consumer attribute) - Annual income
		i. Purpose (Consumer attribute) - Prurpose of taking loan
		j. Dti (Consumer attribute) - ratio montlhy dept to the income
		k. Loan_status   (Loan Attributes) (outcome) - 
		l. Grade, sub_grade  (Loan Attributes) (outcome) - Grades assigned to the borrower based on the performance 
        j. delinq_2yrs (consumer attribute) (output) - Number of 30+ past dues faced by borrower
        h. addr_state (cosumer attribute) - State of the borrower
        i. emp_length - Experience of the borrower in the respective fieldof work

Derived columns

        a. clustered_funded_amnt - grouping of the funcded amounts to borrower ( under 5k, under 10k etc)
        b. clustered_int_rat - Grouping of the interest rate ( 5-10, 10-15 etc)
        c. clustered_annual_inc	 - Grouping of the annual incomes (like under 25k, under 50k etc)
        d. loan_to_income - ratio of the loan amount to the income
        e. installment_to_income - ratio of the installment to the income
        f. inst_to_inc_def	-  based on installemt to income ratio this will take two values(most_likely or less likely) 
        g. ln_to_inc_def  -  based on loan to income ratio category this will take two values(most_likely or less likely)

Data frames: 

        a. sel_loan_df - which contains the column mentioned above for both fully paid and default case
        b. sel_loan_df_def - contains all the columns as that of sel_loan_df only for default case
        c. sel_loan_df_fp - same as b but for fully paid

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.

- This project was submitted as a part of AI ML Course by IIIT - B and upgrad

## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
